\# Binary Search Tree Visualization



An interactive, browser-based visualizer for Binary Search Tree (BST) \*\*insertion\*\* and \*\*deletion\*\*, built with plain HTML, CSS, and JavaScript — no frameworks or dependencies required.



The tool walks through each algorithmic step (comparisons, left/right decisions, node movement, and final placement) while animating the tree as an SVG diagram, so you can \*see\* exactly how a BST insert or delete operation unfolds.



\## Live Demo



Open `dsa6.html` directly in any modern browser — no build step or server needed.



\## Features



\- \*\*Step-by-step insertion\*\* — walk through comparisons one click at a time and watch the algorithm pseudocode highlight the active line as it runs

\- \*\*Instant "Build Full" insert\*\* — insert a whole sequence of values at once to quickly generate a tree

\- \*\*Step-by-step deletion\*\* — visualizes the three deletion cases: leaf node, single child, and two children (via inorder successor)

\- \*\*Live SVG rendering\*\* — nodes and edges are drawn and repositioned automatically as the tree changes, with color-coded highlights for:

&#x20; - 🟡 node currently being compared

&#x20; - 🔵 node being moved to

&#x20; - 🟢 newly inserted / found node

\- \*\*Algorithm reference panels\*\* — side-by-side pseudocode for both insertion and deletion

\- \*\*Reset \& Auto Layout controls\*\* — clear the tree or re-space nodes at any time

\- Supports both numeric and string values



\## How to Use



1\. Open `dsa6.html` in your browser.

2\. \*\*To insert:\*\*

&#x20;  - Enter space- or comma-separated values (e.g. `100 50 150 25 75`) in the \*Insert values\* box.

&#x20;  - Click \*\*Prepare Insert Steps\*\*, then \*\*Next Insert Step\*\* to walk through the algorithm one comparison at a time.

&#x20;  - Or click \*\*Build Full Insert\*\* to construct the tree instantly.

3\. \*\*To delete:\*\*

&#x20;  - Enter a value in the \*Delete values\* box.

&#x20;  - Click \*\*Prepare Delete\*\* and step through with \*\*Next Delete\*\*, or click \*\*Delete Now\*\* to remove it immediately.

4\. Use \*\*Reset\*\* to clear the tree, or \*\*Auto Layout\*\* to re-space nodes after changes.



\## Tech Stack



\- HTML5 + SVG for rendering

\- Vanilla CSS for styling and transitions

\- Vanilla JavaScript (no external libraries or build tools)



\## Project Structure



```

Binary-Search-Tree-Visualization/

└── dsa6.html   # Self-contained app: markup, styles, and logic in one file

```



\## Roadmap / Ideas



\- \[ ] Add traversal visualizations (inorder, preorder, postorder)

\- \[ ] Add balance/height display per node

\- \[ ] Add AVL/self-balancing tree mode

\- \[ ] Mobile-friendly responsive layout



\## License



No license specified yet — consider adding one (e.g. MIT) if you'd like others to reuse this freely.

