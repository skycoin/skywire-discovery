# Skywire discovery server

The discovery server code was pulled out of github.com/skycoin/skywire because it uses sqlite3 as a dependency which requires cgo which imposes constraints on the other users of skywire.

However, the web UI remains in the skywire repo under pkg/net/skycoin-messenger/monitor/web, because the monitor is also used by the manager (if this changes, it can be moved here).
