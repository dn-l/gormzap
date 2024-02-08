# gormzap

Gorm adapter for zap logger

## Usage

Example of usage:

```golang
import "github.com/dn-l/gormzap"

db, err := gorm.Open(mysql.Open(dsn), &gorm.Config{Logger: gormzap.New(logger)})
```
