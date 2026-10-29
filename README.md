# LYV sign

A single-page, phone-friendly signing page for the trademark assignment
contract (عقد تنازل عن علامة تجارية). The signer fills the blanks, signs with a
finger, and downloads the signed contract as an A4 PDF to send back.

`index.html` is self-contained (html2canvas and jsPDF load from cdnjs). It is
served by GitHub Pages from this repository; the workflow in
`.github/workflows/pages.yml` deploys it on every push to `main`.

The page carries a `noindex` tag. Share the link only with the signer.
