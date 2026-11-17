# Mocha in the browser

Live demo: https://shivjain123.github.io/mocha-web-demos/

<img width="921" height="545" alt="image" src="https://github.com/user-attachments/assets/9bb14bfb-3bf1-44ba-8c2c-ca97b8699942" />


A CAPE (convective available potential energy) calculator written in
[Mocha](https://github.com/shivjain123/My_lang_Mocha) and compiled to
WebAssembly with `mocha wasm cape_demo.mch`. The calculation runs entirely
in your browser; the page has no backend.

- Build size: about 59 KB (about 27 KB gzipped)
- Checked against MetPy for a surface-based parcel on this fixed sounding; results are
  typically within a few percent
- Limitation: only the surface temperature and dew point change. If the surface is much
  hotter than the fixed 27 °C layer above it, the result can be far off
- Educational demo, not for forecasting
