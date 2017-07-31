# Paste Image Ftp

Paste image directly from clipboard to markdown/asciidoc(or other file)!

**Support Mac/Windows/Linux!** And support config destination folder.

## Usage

1. capture screen to clipboard
2. Open the command palette: `Ctrl+Shift+P` (`Cmd+Shift+P` on Mac)
3. Type: "Paste Image" or you can use default keyboard binding: `Ctrl+Shift+V` (`Cmd+Shift+V` on Mac).
4. Image will be saved on ftp server
5. The path will be paste to current editing file 

## Config

- `pasteImageFtp.ftpHost`

    The destination ftp server to save image file.    

    
    Default is `""`.

- `pasteImageFtp.ftpUserName`

    The ftp server username.

    
    Default is `""`.

- `pasteImageFtp.ftpUserPwd`

    The ftp server user password.

    Default is `""`.

- `pasteImage.ftpPort`

    The ftp server port.

    Default is `21`.

- `pasteImage.ftpFolder`

    The destination server folder you want to save.

    Default is `""`.

## Format

### File name format

If you selected some text in editor, then extension will use it as the image file name. **The selected text can be a sub path like `subFolder/subFolder2/nameYouWant`.**

If not the image will be saved in this format: "Y-MM-DD-HH-mm-ss.png". 

### File link format

When you editing a markdown, it will pasted as markdown image link format `![](imagePath)`.

When you editing a asciidoc, it will pasted as asciidoc image link format `image::imagePath[]`.

In other file, it just paste the image's path.

## Contact

If you have some any question or advice, Welcome to [issue](https://github.com/MOTK-FED/vscode-paste-image-ftp/issues)
