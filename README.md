# 🌲 XML Tree Visualizer

An interactive, zero-dependency web application to visualize XML data as a beautiful, explorable tree graph. Paste your XML into the live editor and instantly see it rendered as an interactive diagram.

<img width="1915" height="838" alt="image" src="https://github.com/user-attachments/assets/6547b32a-4b5f-4057-85fd-fd6343b7faf5" />


## ✨ Features

-   **Real-time Visualization**: Instantly parses and displays your XML as a tree as you type.
-   **Live XML Editor**: A clean, line-numbered editor to write or paste your XML.
-   **Instant Validation**: Get immediate feedback on whether your XML syntax is valid.
-   **Interactive Tree Controls**:
    -   **Pan & Zoom**: Navigate large trees with intuitive mouse controls.
    -   **Expand & Collapse**: Click on any node to toggle its children.
    -   **Fit to Screen**: Center and fit the entire tree within the viewport.
    -   **Expand/Collapse All**: Quickly show or hide all nodes in the tree.
-   **Responsive Layout**: A resizable split-pane view to adjust the editor and tree panels.
-   **Modern UI**: A sleek, dark-themed interface that's easy on the eyes.
-   **⚡ Zero-Installation**: Runs entirely in the browser from a single `index.html` file. No server, no Node.js, no build steps required.

## 🚀 How to Use

This application is designed for ultimate simplicity.

#### Option 1: Run Locally
1.  **Download**: Download the `index.html` file from this repository.
2.  **Open**: Double-click the file to open it in your favorite modern web browser (like Chrome, Firefox, or Edge).

#### Option 2: Live Demo (via GitHub Pages)
You can easily host this application for free on GitHub Pages.
1.  Go to your repository's **Settings** tab.
2.  Navigate to the **Pages** section on the left sidebar.
3.  Under "Build and deployment", select the source as **Deploy from a branch**.
4.  Choose the `main` branch and the `/ (root)` folder, then click **Save**.
5.  Your live application will be available at `https://<your-username>.github.io/<your-repo-name>/`.

## 🛠️ Technology Stack

This application leverages the power of modern web technologies to run entirely on the client-side, fetching all dependencies from a CDN.

-   **HTML5 & CSS3**: The core structure and styling.
-   **[Tailwind CSS](https://tailwindcss.com/)**: For a utility-first CSS framework to build the modern UI.
-   **[React](https://reactjs.org/)**: For building the user interface with a component-based architecture.
-   **[D3.js](https://d3js.org/)**: The powerhouse behind the data-driven, interactive tree visualization.
-   **[fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser)**: For robust and high-performance XML parsing in the browser.
-   **[Babel Standalone](https://babeljs.io/docs/en/babel-standalone)**: Transpiles JSX and modern JavaScript on-the-fly, directly in the browser, eliminating the need for any build process.

### Why a Single HTML File?

This project is intentionally bundled into a single file to maximize portability and ease of use. This approach is perfect for:
-   **Local Tools**: Keep it on your desktop as a handy utility.
-   **Easy Sharing**: Send the single `index.html` file to anyone, and it will just work.
-   **Simple Demos**: Showcase the power of modern web libraries without any complex setup.

## ✍️ Development & Modification

While the app is a single file, the code is well-structured within the `<script type="text/babel">` tag inside `index.html`. You can edit the React components directly in the HTML file. The code is organized to mirror a standard React project structure, with sections for icons, components (`XmlEditor`, `Header`, `TreeView`), and the main `App` component.

To make changes:
1.  Open `index.html` in a code editor.
2.  Locate the `<script type="text/babel" data-type="module">` tag.
3.  Modify the React/JavaScript code inside.
4.  Save the file and refresh your browser to see the changes.

## 📄 License

This project is licensed under the MIT License.
