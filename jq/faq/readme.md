| **Question**                                              | **Answer**                                                                                 |                                          |
| --------------------------------------------------------- | ------------------------------------------------------------------------------------------ | ---------------------------------------- |
| **Q1. What is `jq`?**                                     | `jq` is a lightweight, command-line tool for processing and transforming JSON data.        |                                          |
| **Q2. How do I install `jq` on Ubuntu?**                  | Run `sudo apt update && sudo apt install jq`.                                              |                                          |
| **Q3. Can I use `jq` on Windows?**                        | Yes, you can install it via Chocolatey or use it inside WSL (Windows Subsystem for Linux). |                                          |
| **Q4. What kind of input does `jq` accept?**              | It accepts well-formed JSON input (objects, arrays, etc.).                                 |                                          |
| **Q5. How do I pretty-print a JSON file using `jq`?**     | Use `jq . filename.json` to format and display the file content.                           |                                          |
| **Q6. How do I extract a specific key from a JSON file?** | Use `jq '.keyname' file.json`.                                                             |                                          |
| **Q7. Can I chain multiple jq commands?**                 | Yes, `jq` supports piping and chaining, like \`jq '.\[]                                    | .name' file.json\`.                      |
| **Q8. Does `jq` support filtering arrays?**               | Yes, you can use filters like \`.\[]                                                       | select(.age > 25)\` for array filtering. |
| **Q9. Is `jq` only for viewing JSON?**                    | No, it also supports transformations, filtering, mapping, and arithmetic.                  |                                          |
| **Q10. Where can I find more examples?**                  | Visit [https://jqlang.org/](https://jqlang.org/) or use `man jq` after installation.       |                                          |
