# ANNScreen

ANNScreen is a macOS-based financial instrument screener using artificial neural networks to perform ML-assisted price action prediction and real-time criteria screening. It primarily uses the excellent [FANN](https://github.com/libfann/fann) library to perform training and model testing.

Currently, ANNScreen is only supports major foreign exchange (FX or forex) currency pairs, although migration to full financial instruments, such as equities, options and futures may be performed later if the underlying behavior of this program is sound.

## Credits

This application makes use of some wonderful libraries and resources to accomplish its task:
  1. [FANN](https://github.com/libfann/fann) - used for the logical core of the application
  2. [Charts](https://github.com/danielgindi/Charts) - used for financial data and statistical visualization
