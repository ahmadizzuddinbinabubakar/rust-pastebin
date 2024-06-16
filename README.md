# PASTEBIN BACKEND USING RUST
## Run project
cargo run

## Example
- upload file:  
                curl \
                -F "userid=1" \
                -F "filecomment=This is an image file" \
                -F "image=@<'filepath'>" \
                  http://localhost:8000
  
<br/>

<img width="565" alt="Screenshot 2024-06-16 at 16 22 16" src="https://github.com/ahmadizzuddinbinabubakar/rust-pastebin/assets/106616443/f34ce58a-4d10-4ee2-af3a-b0c92f9b77c4">
<br/>
<br/>

- receive paste link:
<img width="187" alt="Screenshot 2024-06-16 at 16 31 27" src="https://github.com/ahmadizzuddinbinabubakar/rust-pastebin/assets/106616443/7682dd51-00b8-4d7a-aa07-a3c29780e80f">
<br/>
<br/>

- check upload folder contains file:
<img width="363" alt="Screenshot 2024-06-16 at 16 33 06" src="https://github.com/ahmadizzuddinbinabubakar/rust-pastebin/assets/106616443/2d6dda1e-02e7-464c-9607-f92a7e99de7d">
<br/>
<br/>

- check link for file:
<img width="676" alt="Screenshot 2024-06-16 at 16 34 23" src="https://github.com/ahmadizzuddinbinabubakar/rust-pastebin/assets/106616443/031219bd-8e3f-48bd-95b3-1c7ac98836ef">
