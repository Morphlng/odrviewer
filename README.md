# odrviewer

[odrviewer.io](https://odrviewer.io) is an online OpenDRIVE-file (_.xodr_) viewer.

This repository is primarly for posting and tracking issues, as well as discussing feature requests.
The core of the viewer is closed-source with only the public assets being hosted here.

The viewer is implemented in C++, using WebGL and is based on the open source C++ library [libOpenDRIVE](https://github.com/pageldev/libOpenDRIVE).

<img width="1440" alt="odrviewer" src="https://github.com/pageldev/odrviewer/assets/42587026/5e6066c2-9fab-4fa5-8aae-ed54c0248b1c">

## Usage

This fork is for local-hosting the odrviewer. The resource files are downloaded from the [official websites](https://odrviewer.io), we don't have the original source code.

1. clone this repo

```bash
git clone https://github.com/Morphlng/odrviewer
cd odrviewer
```

2. start a http server

```bash
# You can start the local server using any method, the easiest for me is:
python -m http.server
```