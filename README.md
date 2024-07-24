
# CharacterGenV3_Offline

## Getting Started

Follow the instructions below to set up and run the project on your local machine.

### Prerequisites

- Ensure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. **Clone the repository**:

   ```sh
   git clone https://github.com/0xmetaschool/10k-nft-image-generator.git
   ```

2. **Navigate into the project's directory**:

   ```sh
   cd CharacterGenV3_Offline
   ```

3. **Install all dependencies**:
   ```sh
   npm install
   ```

4. **Create an empty public Github repository and copy its HTTPS link. Paste it in the `.env` file against the `GIT_REPO_URL` variable.**

### Usage

5. **Run the Image and Metadata Generator**:
   ```sh
   node generate.js
   ```

6. **Once the process completes, the metadata and images will be generated in the project directory under two folders named**:

   - generated_images
   - generated_metadata

7. **To upload the files to the GitHub repository, run**:
   ```sh
   node upload.js
   ```

8. **Once the upload is complete, go to your GitHub repository's settings and under "Code and automation", select "Pages". Set the source to "Deploy from branch" and select the master branch if not set by default. Click save and after a few minutes, your GitHub Pages will be live.**
