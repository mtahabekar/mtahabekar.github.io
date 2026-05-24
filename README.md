# Taha Bekar Personal Website

Static GitHub Pages portfolio for Taha Bekar, focused on robotics software engineering, perception, SLAM, LiDAR point cloud processing, sensor fusion, ROS, and autonomous systems.

## Local Preview

Open `index.html` directly in a browser, or run a simple static server from the repository root:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

If Python is not available, any static file server will work because the site has no backend, build step, or database.

## Deployment

Deploy directly with GitHub Pages from the main branch. The homepage is `index.html`, and project pages live in `projects/`.

## Assets

Current media wiring:

- `assets/Taha_Bekar_CV.pdf` is linked from the hero and resume sections.
- `assets/images/deformable-manipulation.png` is used on the homepage and project detail page.
- `https://youtu.be/qcqMBeMrgU0` is embedded for the autonomous UGV mapping project.
- `assets/images/parking-detection.mp4` is used on the homepage and project detail page.
- `assets/images/lidar-slam.jpg` still needs to be added.
- `assets/images/profile.jpg` still needs to be added or exported from `assets/images/profile.HEIC`; JPG or PNG is recommended for browser compatibility.
- Optional project images or videos for lane detection and FPGA QoS projects

Remaining placeholders are kept in the HTML so the layout remains clean until real media is added.
