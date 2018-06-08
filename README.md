# go-talib

Version of [go-talib](https://github.com/markcheno/go-talib) that uses [decimals](https://github.com/shopspring/decimal) instead of floats

Decimals will be slightly less performant than float64s (or big.Rats, or big.Floats),
but in some cases their precision is worth the trade off

## Install

Install the package with:

```bash
go get github.com/BlockchainAnalyticsLLC/gota.git
```

Import it with:

```go
import "github.com/BlockchainAnalyticsLLC/gota.git"
```

and use `talib` as the package name inside the code.

## Example


## License

MIT License  - see LICENSE for more details
