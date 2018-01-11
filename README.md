# tesseract-OCR-with-react-native-along-with-image-path-edit

RNTesseractOcr.recognize(imgPath, lang, tessOptions)
  .then((result) => {
    this.setState({ ocrResult: result });
    console.log("OCR Result: ", result);
  })
  .catch((err) => {
    console.log("OCR Error: ", err);
  })
  .done();
