# ZZ-doupe

# Optimize images
run in folder with images to do batch optimization
```
find . -type f \( -iname "*.jpg" -o -iname "*.jpeg" \) -exec sh -c '
  cwebp -q 80 -resize 1200 0 "$1" -o "${1%.*}.webp"
' _ {} \;
```