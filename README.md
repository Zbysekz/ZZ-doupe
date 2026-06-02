# ZZ-doupe

## Run locally

**Requirement:** Hugo ≥ 0.116.0 (`sudo apt install hugo` or https://gohugo.io/installation/)

```bash
hugo server
```

Open http://localhost:1313 in your browser. The server hot-reloads on file changes.

To include draft posts:

```bash
hugo server -D
```

---

# Optimize images
`sudo apt install convert`

run in folder with images to do batch optimization
```
find . -type f \( -iname "*.jpg" -o -iname "*.jpeg" \) -exec sh -c '
  convert "$1" -auto-orient -resize 1200x -strip -quality 82 "${1%.*}.webp"
' _ {} \;
```