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
- `https://youtu.be/EaQOPBVk_W0` is embedded for the deformable manipulation project on the homepage and detail page.
- `https://youtu.be/Qf5c9lpxdgU` is embedded as the main LiDAR-IMU SLAM video on the homepage and detail page.
- `https://youtu.be/Uy0nLalF4dU` is embedded as the second LiDAR-IMU SLAM video on the detail page.
- `https://youtu.be/qcqMBeMrgU0` is embedded for the autonomous UGV mapping project.
- `https://youtu.be/VNDclh1NsIs` is embedded for the parking detection project on the homepage and detail page.
- `https://youtu.be/I0izUzpThkc` is embedded for the lane detection project card.
- `assets/images/fpga.jpg` is used for the FPGA Network QoS Controller project card.

Remaining placeholders are kept in the HTML so the layout remains clean until real media is added.
