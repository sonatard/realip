# realip

Client real IP Address from HTTP Request. https://go.dev/play/p/j8356cc-Z8j

- Fix multiple X-Forwarded-For headers https://github.com/tomasen/realip/pull/8
- Use modern net/netip package
- IPv4 and IPv6 support
- Support for multiple types client IP address header
- A simple function

## Why not package?

A little copying is better than a little dependency.
https://go-proverbs.github.io/
