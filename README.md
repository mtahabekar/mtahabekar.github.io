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
- `assets/images/profile.jpg` is used in the hero section.
- `assets/images/deformable-manipulation.png` is used on the homepage and project detail page.
- `assets/images/lidar-slam-1.mp4` is used as the main LiDAR-IMU SLAM video on the homepage and detail page.
- `assets/images/lidar-slam-2.mp4` is shown on the LiDAR-IMU SLAM detail page.
- `https://youtu.be/qcqMBeMrgU0` is embedded for the autonomous UGV mapping project.
- `assets/images/parking-detection.mp4` is used on the homepage and project detail page.
- Optional project images or videos for lane detection and FPGA QoS projects

Remaining placeholders are kept in the HTML so the layout remains clean until real media is added.
