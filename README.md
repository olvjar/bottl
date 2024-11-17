# bottl
A simple command-line tool written in Rust designed to shorten URLs, as well read and generate QR codes for easy sharing and access.

## Features
- Convert long URLs into short, shareable links.
- Custom short-links: Specify a custom slug for the shortened URL.
- Generate QR Codes: Export as a vector or image.
- Link Expiration: Limit access to short URLs, by date range and/or maximum number of visits.

## Prerequisites
- Rust (1.50.0 or later)
- SQLite (optional, but included with the Rust crate)