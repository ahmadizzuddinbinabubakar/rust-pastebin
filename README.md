# PASTEBIN BACKEND USING RUST
## Run project
cargo run

## Example
- upload file:  curl \
                -F "userid=1" \
                -F "filecomment=This is an image file" \
                -F "image=@<'filepath'>" \
                  http://localhost:8000

