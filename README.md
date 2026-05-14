# ZZ-doupe

# Optimize images
`sudo apt install convert`

run in folder with images to do batch optimization
```
find . -type f \( -iname "*.jpg" -o -iname "*.jpeg" \) -exec sh -c '
  convert "$1" -auto-orient -resize 1200x -strip -quality 82 "${1%.*}.webp"
' _ {} \;
```