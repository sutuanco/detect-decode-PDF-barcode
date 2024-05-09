Program for extracting multiple barcode from a PDF file
It's solved but time to processing is still high

Step to step
1. get barcode by processing image -> thresholding -> comparing width, high (all barcode is same size)
2. decode barcode by zxing library (extracted all barcode but very slow) 