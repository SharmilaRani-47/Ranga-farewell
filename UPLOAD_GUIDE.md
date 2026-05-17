# How to Upload Images and Videos

## 📁 Folder Structure

Your repository now has this structure:

```
Ranga-farewell/
├── index.html           # Main webpage
├── styles.css           # Styling
├── script.js            # Interactivity
├── README.md            # Documentation
├── images/              # 👈 Place images here
│   ├── gallery-1.jpg
│   ├── gallery-2.jpg
│   └── ...
└── videos/              # 👈 Place videos here
    ├── video-1.mp4
    ├── video-2.mp4
    └── ...
```

---

## 🖼️ Adding Images

### Method 1: Using GitHub Web Interface (Easy)

1. Go to: https://github.com/SharmilaRani-47/Ranga-farewell
2. Click the **`images/`** folder
3. Click **"Add file"** → **"Upload files"**
4. Drag & drop your images or click to select
5. Name them: `gallery-1.jpg`, `gallery-2.jpg`, etc.
6. Click **"Commit changes"**

### Supported Image Formats:
- ✅ JPG/JPEG (best for photos)
- ✅ PNG (for graphics with transparency)
- ✅ WebP (modern format)
- ✅ GIF (animated images)

### Recommended Sizes:
- Width × Height: 500px × 500px minimum
- High quality: 1200px × 1200px or larger

---

## 🎬 Adding Videos

### Method 1: Using GitHub Web Interface (Easy)

1. Go to: https://github.com/SharmilaRani-47/Ranga-farewell
2. Click the **`videos/`** folder
3. Click **"Add file"** → **"Upload files"**
4. Select your MP4 video files
5. Name them: `video-1.mp4`, `video-2.mp4`, etc.
6. Click **"Commit changes"**

### Supported Video Formats:
- ✅ MP4 (H.264 codec) - Most compatible
- ✅ WebM
- ✅ OGG

### Recommended Video Specs:
- Format: **MP4**
- Codec: H.264 video + AAC audio
- Resolution: 720p (1280×720) or 1080p (1920×1080)
- File size: Keep under 100MB for faster loading

### How to Convert Videos:
Use **HandBrake** (free):
1. Download: https://handbrake.fr/
2. Open your video
3. Select "Fast 1080p30" preset
4. Export as MP4
5. Upload to videos folder

---

## 📝 HTML References

Once you upload files, the HTML automatically references them:

### Images
```html
<!-- Already configured in index.html -->
<img src="images/gallery-1.jpg" alt="Your Photo 1">
<img src="images/gallery-2.jpg" alt="Your Photo 2">
```

### Videos
```html
<!-- Already configured in index.html -->
<video controls>
    <source src="videos/video-1.mp4" type="video/mp4">
</video>
```

---

## 🚀 Step-by-Step Upload Guide

### Upload Images:

1. Visit: https://github.com/SharmilaRani-47/Ranga-farewell/tree/main/images
2. Click **"Add file"** button
3. Click **"Upload files"**
4. Drag and drop your images
5. Click **"Commit changes"**
6. Wait 1-2 minutes for site to update

### Upload Videos:

1. Visit: https://github.com/SharmilaRani-47/Ranga-farewell/tree/main/videos
2. Click **"Add file"** button
3. Click **"Upload files"**
4. Select your MP4 files
5. Click **"Commit changes"**
6. Wait 1-2 minutes for site to update

---

## ✅ File Naming Convention

**Keep it simple:**

```
✅ Good:
- gallery-1.jpg
- gallery-2.jpg
- video-1.mp4
- video-2.mp4

❌ Avoid:
- my photo (spaces)
- Photo!@#$.jpg (special characters)
- 很长的中文文件名.jpg (non-ASCII)
```

---

## 🔧 Customizing the HTML

To add more gallery items, edit `index.html`:

```html
<!-- Add new gallery item -->
<div class="gallery-item">
    <img src="images/gallery-7.jpg" alt="Your Photo 7">
    <p>Your Photo 7</p>
</div>
```

To add more videos:

```html
<!-- Add new video item -->
<div class="video-item">
    <h3>Your Video 3</h3>
    <video width="100%" controls>
        <source src="videos/video-3.mp4" type="video/mp4">
    </video>
</div>
```

---

## 💡 Pro Tips

1. **Optimize before uploading**: Compress images to reduce file size
2. **Use descriptive names**: Makes it easier to manage files
3. **Keep folder organized**: All images in `images/`, all videos in `videos/`
4. **Test before uploading**: Make sure files play/display correctly
5. **Backup originals**: Keep original files elsewhere

---

## 🎯 Your Sites Will Show:

✅ **Images folder**: `images/gallery-1.jpg`, `gallery-2.jpg`, etc.  
✅ **Videos folder**: `videos/video-1.mp4`, `video-2.mp4`, etc.  
✅ **Auto fallback**: If local files missing, uses sample images from Unsplash

---

## 📞 Need Help?

Visit the images or videos folder in your repository and click **"Upload files"** button!

**Example URLs:**
- Images: https://github.com/SharmilaRani-47/Ranga-farewell/tree/main/images
- Videos: https://github.com/SharmilaRani-47/Ranga-farewell/tree/main/videos

---

**Your portfolio will automatically use these files once uploaded!** 🎉
