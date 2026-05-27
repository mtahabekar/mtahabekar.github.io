# Taha Bekar Personal Website

Static GitHub Pages portfolio for Taha Bekar, focused on robotics software engineering, perception, SLAM, LiDAR/IMU sensor fusion, ROS/ROS 2, simulation, and autonomous systems.

The site is plain HTML/CSS and does not use a build step, backend, database, npm dependency, or framework.

## Local Preview

Run a simple static server from the repository root:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

Opening `index.html` directly in a browser also works for most pages, but a local static server better matches GitHub Pages behavior for PDF embeds.

## Deployment

Deploy directly with GitHub Pages from the main branch. The homepage is `index.html`, project pages live in `projects/`, shared styles live in `css/`, and PDFs/media live in `assets/`.

## Project PDFs

- Real-Time Cloth Simulation report: stored in `assets/` and downloadable from `projects/deformable-object-manipulation.html`.
- Autonomous UGV poster: stored in `assets/` and embedded directly on `projects/ugv-mapping.html`, with a fallback PDF link.

## Current Media Wiring

- `assets/Taha_Bekar_CV.pdf` is linked from the hero and resume sections.
- `assets/images/profile.jpg` is used in the hero section.
- `https://youtu.be/EaQOPBVk_W0` is embedded for the deformable manipulation project on the homepage and detail page.
- `https://youtu.be/Qf5c9lpxdgU` is embedded as the main LiDAR-IMU SLAM video on the homepage and detail page.
- `https://youtu.be/Uy0nLalF4dU` is embedded as the second LiDAR-IMU SLAM video on the detail page.
- `https://youtu.be/qcqMBeMrgU0` is embedded for the autonomous UGV project on the homepage and detail page.
- `https://youtu.be/VNDclh1NsIs` is embedded for the parking detection project on the homepage and detail page.
- `https://youtu.be/I0izUzpThkc` is embedded for the lane detection project card.
- `assets/images/fpga.jpg` is used for the FPGA Network QoS Controller project card.
