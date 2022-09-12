langkah-langkah

1. ubah sass ke css standar
   bisa pake command:
    - sass .
    - sass --watch .

2. compress (jadi 1 baris)
   bisa pake command
    - sass folder_sass/ --style=compressed => sass map-each/ --style=compressed

3. autoprefixer dari postcss
   - install: npm install postcss-cli autoprefixer
   - generate: 
     npx postcss folder/file_css --use autoprefixer -d folder_generate/
     npx postcss sass/style.css --use autoprefixer -d build/