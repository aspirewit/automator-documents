# Automator Documents

## Services

### 1. Upload images to Qiniu (for Markdown)

#### Installation
1. Download [qrsctl](http://devtools.qiniu.com/darwin/amd64/qrsctl?ref=developer.qiniu.com) to `/usr/local/bin/` directory and add execute permissions to it
2. Create `~/.upload_images_to_qiniu` file and fill in the following configuration
```
username=""
password=""
bucket=""
domain=""
```

#### Usage
1. After selecting the images, from the services section of the right-click menu to find "Upload images to Qiniu" and click it
2. After uploading the images, the message "Uploaded successfully!" will be displayed
3. Paste the tags into the markdown text
