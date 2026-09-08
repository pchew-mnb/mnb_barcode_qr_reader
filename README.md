# mnb_barcode_qr_reader

A QR code and barcode scanner web application using WebAssembly.

## Features

- Real-time barcode and QR code scanning via camera
- Upload and scan static image files
- Supports multiple barcode formats (Code-39, Code-93, Code-128, EAN, UPC, ISBN, QR, and more)
- Lightweight, runs in modern browsers

## Dependencies

This project uses the following open-source library:

- **[@undecaf/zbar-wasm](https://github.com/undecaf/zbar-wasm)** v0.11.0 - A WebAssembly build of ZBar Bar Code Reader
  - Licensed under [LGPL-2.1+](http://opensource.org/licenses/LGPL-2.1)
  - Original ZBar project: https://github.com/mchehab/zbar

## License

This project is licensed under the **GNU Lesser General Public License v2.1 or later (LGPL-2.1+)** - see the [LICENSE](LICENSE) file for details.

### License Compatibility Note

This project is distributed under LGPL-2.1+ to comply with the licensing requirements of the zbar-wasm library it depends on. The LGPL-2.1+ license allows this software to be used, modified, and distributed freely, with the requirement that modifications to the library itself must also be shared under compatible terms.