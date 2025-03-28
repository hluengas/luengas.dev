---
sitemap: false
layout: archive
classes: wide
permalink: /resume/
---

# Henry Luengas

<a href="mailto:contact@luengas.dev" class="btn btn--info btn--primary">Email</a>
<a href="https://www.linkedin.com/in/henry-luengas" class="btn btn--info btn--primary">LinkedIn</a>
<a href="https://github.com/hluengas" class="btn btn--info btn--primary">Github</a>
<a href="/assets/documents/HenryLuengas-Resume.pdf" class="btn btn--warning btn--primary">Resume PDF</a>

*****

## Education

California Polytechnic State University San Luis Obispo

**(Cal Poly) - College of Engineering:** B.S. in **Computer Science**

Graduation: June 2020

*****

## Skills

* **Programming Languages:** Bash, Python, Rust, Go, JavaScript, C, C++, Markdown, Julia, Elm, Java
* **Systems & Frameworks:** Linux, Containers, Azure, Kubernetes, AKS, Terraform, Helm, Ansible, Chef, WSL, Tailscale, SQL, OAuth, OIDC, WebAuthn, Draw.io OpenGL, OpenCL, Unity3D, MS Visio
* **Network Infrastructure:** TCP/IP, VLAN, 5G Core & RAN, WiFi, SDN, Wireguard, Structured Cabling

*****

## Work Experience

**AT&T CIO Automation Platforms Development** - Senior Software Engineer

(Oct 2022 – Present)

* Shared Platform Ops Team
  * Deployed, maintained, and supported six shared platforms used by AT&T developers hosting service delivery and service assurance applications on premise and in Azure.
  * Served as system administrator for 52 AKS clusters comprised of 1,500+ VMs with over 42,000
cores required for daily operation of 25+ internal development teams
  * Designed and deployed Azure infrastructure to host the AT&T Software Symposium website using Terraform and Azure DevOps (ADO) pipelines for a structured IaC deployment
  * Modernized Software Symposium website through redevelopment on a new tech stack and reimplementation using Azure Infrastructure as a Service (IaaS) resources
  * Adapted site to cloud native design and created container based CI/CD GitHub Action workflows for the development team

**AT&T CIO Technology Development Program** - Network Engineer

(Jan 2021 - Oct 2022)

* Software Engineer – Wireless Technology, Network Analytics & Automation
  * Containerized an app used for daily analysis of Passive Intermodulation (PIM) at network cell sites
  * Deployed the app to a Kubernetes cluster on Azure using Terraform and Helm
* Specialized Networks Consultant – Consulting, Mobility & IoT Professional Services
  * Developed, deployed, and presented 5G & IoT technical demonstrations highlighting video intelligence use cases for warehouse logistics to Private Cellular Network customers
  * Implemented a containerized video transcoding app to stream 5G camera footage to internet video platforms using Docker and FFMPEG, as a technical demo for Private Cellular Networks
  * Served as an administrator for the AT&T 5G Technical Associate Certification Course and as instructor for the section on container virtualization, CNFs, and VNFs
* Data Steward – Network Cloud, Blue Train Fabric Automation
  * Automated cleaning and formatting process for physical and virtual network device setup data used by AT&T’s internal cloud platform using Python and Microsoft Excel

**Cal Poly Student Affairs Technology** - IT Specialist

(Apr 2016 - Jun 2020)

* Diagnosed, and resolved issues with the campus housing network and servers.
* Provided technical support (software & hardware) for users of the campus network.
* Maintained an internal website used to provide support to students in housing.

**UHV Technologies** - Engineering Intern

(May 2015 – Sep 2015)

* Assisted in the design process, digitizing and modeling engineering plans with CAD.
* Prototyped a linear encoder measurement device (hardware and software).

*****

## Certifications

* SAFe 5 Agilist Certification - Scaled Agile - Mar 2021
* 5G Technical Associate Certification - AT&T Consulting - Mar 2022

*****

## Projects

### Ray Traced Photorealistic Video Renderer

* Developed a multithreaded and object-oriented C++ image render that utilizes a spatial data-structure
* The program parses and renders a subset of the POV-Ray scene description standard
* Features include a Cook-Torrance BDRF, reflection, refraction, shadowing, and Fresnel effects
* Planes, triangles, spheres, boxes, and multiple lights are all supported and can use matrix transformations
* The renderer applies rudimentary kinematics to produce successive frames for an output video

### Tie-Dye Pixel Art Renderer

* Wrote a renderer in Python demonstrating various methods of process acceleration
* Implemented sequential and parallel running modes to assess performance of CPU parallelism
* Implemented a GPU compute mode with OpenCL showing process scaling to hundreds of workers
* Implemented an R* Tree spatial data structure to highlight speed increase from an optimized algorithm

### 3D Marble Run Platformer Game

* Collaborated with a group to create a game from scratch in C++ and OpenGL
* Features include physics simulation, a spatial data structure, PBR shaders, shadow-mapping, environmentmapping, view frustum culling, positional audio, enemy AI, and an adjustable third person camera

### Music Visualizer

* Coded an interactive audio visualization program in C++ and OpenGL using audio captured from the system
* Programmed a procedural landscape with variable height based on Fast Fourier transform of the audio

### AI Video Summarization Tool

* Worked with a group to create a utility to pare down security camera footage using AI image recognition
* Developed in Python using YOLOv3 for object detection and OpenCV for image manipulation

### Networked Chat App and Packet Analyzer

* Wrote client and server programs in C that use TCP to convey custom message packets between users
* Created a utility in C that uses NPCAP to inspect packets, functioning like a basic version of Wireshark

### Animation Blending in OpenGL

* Created an animation in C++ and OpenGL where a model skeleton goes through a series of dances with animation blending
* The models and dance animations were extracted from the Unreal Engine game Fortnite.

### Unix System Stats Logger

* Wrote a CLI program in C to query unix system files for system and running process stats to be logged periodically to a file

### System Building & Networking

* Built a virtualization server to use as a NAS, DNS resolver, Sophos UTM security gateway, and Docker host

### Hangman WebApp (hangman.luengas.dev)

* Built a hangman webapp using Elm to learn more about web development and functional programming
