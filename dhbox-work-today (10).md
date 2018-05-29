    1  mkdir ocr-test
    2  cd ocr-test
    3  sudo apt-get install tesseract-ocr
    4  sudo apt-get install imagemagick
    5  convert -density 300 ~/war-diary/e001518087.jpg -depth 8 -strip -background white -alpha off e001518087.tiff
    6  tesseract e001518087.tiff output.txt
    7  history > dhbox-work-today.md
