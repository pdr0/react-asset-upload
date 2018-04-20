
# React Asset Upload

### Version
This is a Beta

### Description

React component to upload documents

![](https://img.shields.io/github/release/pandao/editor.md.svg)
![](https://img.shields.io/github/issues/pandao/editor.md.svg)
![](https://img.shields.io/bower/v/editor.md.svg)

### How it works

`npm i react-asset-upload`

`import FileUpload from 'react-asset-upload';`

`
<FileUpload
    id='file-uploader'
    name='file1'
    accept="image/gif, image/jpg, image/jpeg, image/png, image/bmp, .pdf"
    className='your-file-uploader-class'
    placeholder='Choose file'
    onChange={yourHandlerHere}
/>

<label for='file-uploader' className='your-class-here'>Choose file</label>
`

You can put `<label>` to apply your style and then, it will trigger `<FileUpload>` at onclick event or just keep it simple without label.
