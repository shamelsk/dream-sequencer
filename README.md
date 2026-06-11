# Dream Sequencer : oh to dream but virtually | a virtual dream

The **Dream Sequencer** is an interactive, web-based tool that allows users to generate unique, mesmerizing visual and auditory experiences based on a seed phrase. By entering a custom phrase, users can create a dynamic particle animation along with an evolving soundscape, making each sequence completely unique.

##  Features

- **Custom Seed Input**: Enter a seed phrase (e.g., "cosmic voyage") to generate unique dream sequences.
- **Particle Animation**: A beautiful particle system that responds to the seed phrase and the user's mouse movement.
- **Audio Generation**: Experience evolving soundscapes generated based on the seed phrase, with adjustable volume.
- **Save & History**: Save your favorite dream sequences and revisit them later through the history section.
- **Responsive Design**: Works seamlessly on all screen sizes.

##  How to Use

1. **Enter a Seed Phrase**: Type a custom phrase (or use the default "cosmic voyage") in the input field.
2. **Generate Dream**: Click "Generate Dream" to create a unique visual and sound sequence.
3. **Save Dreams**: Click "Save Dream" to store your generated sequence for later.
4. **Random Seed**: Click "Random Dream" for an automatically generated seed phrase.
5. **Sound Control**: Adjust the volume or toggle sound playback using the "Play" button.

##  Technologies Used

- **HTML**: For structuring the webpage and input elements.
- **CSS**: For styling the page, including animations and responsiveness.
- **JavaScript**: For creating the particle system, sound generation, and interactive features.


## 🐳 Docker Support

This project now includes Docker and Docker Compose support for simplified deployment and portability.

### Dockerfile

Build the Docker image locally:

```bash
docker build -t dream-sequencer .
```

Run the container:

```bash
docker run -d \
  --name dream-sequencer \
  -p 80:80 \
  dream-sequencer
```

Access the application:

```text
http://localhost
```

---

### Docker Compose

Build and start the application:

```bash
docker compose up -d --build
```

Stop the application:

```bash
docker compose down
```

---

## 🚀 Contribution

The following enhancements were contributed by **Shamel Khan**:

* Added Docker containerization support using Nginx.
* Added Docker Compose configuration for simplified deployment.
* Improved project documentation with Docker setup instructions.
* Enhanced project deployment workflow for local and cloud environments.
* Updated repository structure for easier onboarding and execution.

These changes do not modify the core particle generation or audio synthesis logic and are focused on deployment, portability, and developer experience.

---

## 🙌 Credits

Original Project Author: **Rajnandini**

Original Repository:
https://github.com/rajnyandini/Dream-Sequencer

Dockerization, deployment improvements, and documentation enhancements contributed by **Shamel Khan**.


##  Preview  

<img src="https://raw.githubusercontent.com/rajnandiniini/Dream/main/images/p1.png" width="300" height="auto">
<img src="https://raw.githubusercontent.com/rajnandiniini/Dream/main/images/p2.png" width="300" height="auto">
<img src="https://raw.githubusercontent.com/rajnandiniini/Dream/main/images/p3.png" width="300" height="auto">
<img src="https://raw.githubusercontent.com/rajnandiniini/Dream/main/images/p4.png" width="300" height="auto">




## ⚙️ Setup  

Try it here: **[Dream Sequencer](https://rajnyandini.github.io/Dream-Sequencer/)**  
keep dreaming!!!
