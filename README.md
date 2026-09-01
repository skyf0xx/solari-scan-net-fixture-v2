# solari-scan-net-fixture

Minimal throwaway fixture repository used to test
[solari-scan](https://github.com/skyf0xx/solari-scan)'s network-finding
report. This repo intentionally makes a non-allowlisted outbound network
call (`curl https://example.com`) from its `postinstall` script.

Not intended for any other use.
