# qBittorrent Service

A simple library/service for interacting with qBittorrent API.

I wrote this for use in [qbit-unstaller](https://edholm.dev/qbit-unstaller) and [qbit-exporter](https://edholm.dev/qbit-exporter)

## Configuration

Uses [viper](https://github.com/spf13/viper) for getting configuration values.
Currently, the following config parameters are used. Bind or set them however you want.
```go
func init() {
    viper.SetDefault("username", "admin")
    viper.SetDefault("password", "adminadmin")
    viper.SetDefault("url", "http://localhost:8008")
}
```

## See also

[qBittorrent API specification](https://github.com/qbittorrent/qBittorrent/wiki/Web-API-Documentation)