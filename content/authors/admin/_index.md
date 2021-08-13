---
# Display name
name: Filip Mazurek

# Username (this should match the folder name)
authors:
- admin

# Is this the primary user of the site?
superuser: true

# Role/position
role: Electrical & Computer Engineering PhD Student

# Organizations/Affiliations
organizations:
- name: Duke University
  url: "https://www.duke.edu/"

# Short bio (displayed in user profile at end of posts)
bio: My research interests lie in control systems and support infrastructure for quantum computers, such as control software, compilation, and error characterization.

interests:
- Quantum computing
- Trapped ion control frameworks
- Error simulation

education:
  courses:
  - course: Ph.D. in Electrical Engineering
    institution: Duke University
    year: 2026 expected
  - course: B.S. in Computer Science
    institution: Duke University
    year: 2018

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/widgets/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
- icon: envelope
  icon_pack: fa
  link: 'mailto:filip.mazurek@duke.edu'  # For a direct email link, use "mailto:test@example.org".
- icon: linkedin
  icon_pack: fab
  link: https://www.linkedin.com/in/f-mazurek/
- icon: github
  icon_pack: fab
  link: https://github.com/filipmazurek
# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.  
- icon: cv
  icon_pack: ai
  link: files/resume_fall20.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ""

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.  
user_groups:
- Researchers
- Visitors
---

I am a second-year graduate student in Electrical and Computer Engineering at [Duke University](https://www.https://ece.duke.edu/.edu/) advised by [Professor Ken Brown](https://ece.duke.edu/faculty/kenneth-brown). My broad area of research is Quanutm Computing, and my main focus is working on support software for ion trap quantum computers. I am busy contributing to [Duke ARTIQ Extensions](https://gitlab.com/duke-artiq/dax) (DAX), an open-source project from Duke University focused on adding traditional software abstractions on top of [ARTIQ](https://m-labs.hk/experiment-control/artiq/), a leading control system for quantum information experiments. The goal of the project is to provide a framework that enables the development of modular and transparently layered software for quantum control systems.

I aim to expand DAX further, such as by adding realistic simulation of errors characterized by our actual quantum systems at Duke University. There already exist plans for a middle-level language called DAX.program that sits between higher-level languages such as Qiskit and DAX. My other research interests include strategies for compilation from higher-level languages such as Qiskit to DAX.program as well as optimization strategies for compiling DAX.program to DAX and ARTIQ, and the corresponding system pulses that come with it.
