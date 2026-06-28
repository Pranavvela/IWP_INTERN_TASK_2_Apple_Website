# Project Report: Apple (India) Premium Experience Replication

1. **Team Name:** [Insert Team Name, e.g., Ignite]
2. **Assigned Platform:** Apple Website (Replicated Premium Experience)
3. **Team Leader Name:** Pranav vela
4. **Team Leader GitHub Profile Link:** https://github.com/Pranavvela
5. **Project GitHub Repository Link:** https://github.com/Pranavvela/IWP_INTERN_TASK_2_Apple_Website.git
6. **Project Deployment Link:** https://pranavvela.github.io/IWP_INTERN_TASK_2_Apple_Website/index.html
7. **List of Team Members:**
   1. Pranav vela
   2. [Insert Team Member 2 Name]
   3. [Insert Team Member 3 Name]
   4. [Insert Team Member 4 Name]
8. **Role of each member:**
   1. **Pranav vela** – Lead Developer (HTML/CSS layout structure, CSS-only Mobile/Customizer Interactions, multi-page routing, Git repository setup & push)
   2. **[Member 2]** – UI Enhancements & Image Asset Optimization
   3. **[Member 3]** – Subpage layouts and directory styling
   4. **[Member 4]** – Testing, Cross-browser Verification & Documentation
9. **Contribution of each member (in percentage):**
   1. **Pranav vela** – 40% (or adjust accordingly)
   2. **[Member 2]** – 20%
   3. **[Member 3]** – 20%
   4. **[Member 4]** – 20%
10. **Brief description of each member's contribution:**
    - **Pranav vela** – Developed the main landing page and header structure. Integrated the CSS-only checkbox toggle for responsive mobile menus and custom radio selectors for interactive choice selections (color, size, storage) on product detail pages. Organized static file structures, deleted legacy JS files, and managed Git operations.
    - **[Member 2]** – Assisted in enhancing product page image layout cards and sizing grids. Verified high-quality responsive scaling on different viewports and ensured pixel-perfect alignment.
    - **[Member 3]** – Created subpages for the Apple Watch, AirPods Pro, and MacBook models. Linked page navigation cards so each "Learn More" and "Buy" button routes to its respective detail view.
    - **[Member 4]** – Tested navigation menus, mega menus, buttons, and responsive styles for bugs. Documented layout transitions, checkout bag additions, and drafted report materials.
11. **Any challenges faced and how your team solved them:**
    - **JavaScript-Free Selectors:** Designing dynamic highlights for active states (such as selecting a storage or size button) without using any JavaScript was initially challenging. The team resolved this by using hidden HTML radio inputs coupled with styled `<label>` elements and CSS sibling selectors (`input[type="radio"]:checked + label`).
    - **Multi-Page Static Navigation:** Converting the website from a single-page modal-based layout to a modular multi-page static flow required meticulous linking across all product listings. We solved this by mapping out the page routing first and updating navbar category links uniformly.
    - **Git Asset Management:** Pushing large image assets to the repository after HTML/CSS code was updated presented errors. We addressed this by cloning the repository locally, structuring folders cleanly, and staging the `assets/` folder separately prior to execution.
