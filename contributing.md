# Contributing to Engineering Prompts

Thank you for considering contributing to **Engineering Prompts**! We welcome contributions from everyone, and there are a few guidelines to make the process smooth and easy.

## How to Contribute

1. **Fork the Repository:**
   Start by forking the repository to your GitHub account and cloning it to your local machine.

2. **Create a New Branch:**
   Create a new branch for your contribution, such as `feature/your-feature-name`.

3. **Add Your Prompt Chain:**
   Navigate to the appropriate section in **README.md** based on the domain your prompt belongs to. If your prompt doesn't fit into any of the existing sections, feel free to create a new one under the corresponding category.

4. **Update the README:**
   Provide a clear description for your prompt chain. Use the format:

   ```
   ### **{Domain Name}**

   - **{Use Case Name}**  
     "{Prompt Chain}"
   ```

5. **Test Your Changes:**
   Ensure your prompt is correctly formatted and works as expected.

6. **Submit a Pull Request:**
   After making your changes, push them to your fork and create a pull request. Be sure to include a description of your changes and why you think it adds value to the repository.

## Guidelines

* **Be Clear:** Ensure the prompt chain is easy to follow and provides clear context.
* **Be Concise:** Keep the prompts concise and to the point, avoiding unnecessary fluff.
* **Be Descriptive:** Provide enough information so someone unfamiliar with the task can understand and use the prompt effectively.

---

## Adding a New Use Case or Domain

#### If it fits into an existing domain:
1. Navigate to the appropriate domain folder inside the `domains/` directory.
2. Open its `README.md`.
3. Add your new use case as a bullet point or sub-section in that file.
4. Follow the existing formatting for consistency.

#### If it's a completely new domain:
1. Inside the `domains/` directory, create a new folder with a meaningful name (e.g., `mobile-development`).
2. Inside that folder, create a `README.md` file.
3. Add your use cases and prompts inside this new `README.md`.
4. At the bottom of the main `README.md` (root level), add a new entry to the Table of Contents linking to your new domain:

```md
  [Mobile Development](domains/mobile-development/README.md)
```
---


## Thank You!

We truly appreciate your contributions! By helping us expand and improve this collection of prompts, you’re making it easier for developers to work more efficiently and with less effort.

Happy Prompting! 🚀