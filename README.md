<p align="center">
  <img src="./nbb.png" alt="NBB 1.1.0 License" width="240">
</p>

# NBB 1.1.0 License
**No Business Boycott License**

Official repository for the **NBB 1.1.0 (No Business Boycott)** license — a database licensing standard designed to protect open datasets, ban lists, and registries from unauthorized commercial resale, scraping, and game-server integration without permission.

---

## Key Rules Summary
* **Personal & Research Use:** Viewing, analyzing, and modifying local copies for non-commercial research is permitted.
* **No Commercial Resale:** Selling, renting, or monetizing access to the database is strictly prohibited.
* **No Unauthorized Game/API Integration:** Deploying the dataset via automated APIs, mirrors, or game servers (e.g., Roblox experiences) without explicit authorization or an active subscription from the Original Author is prohibited.
* **Mandatory Attribution:** Any public display or project using the data must include a visible link to the Original Author's source.
* **Viral Scope:** Even if 99% of the original dataset is deleted or altered, the license remains fully binding as long as at least **one (1) record** from the original database remains.

---

## How to Apply to Your Database

1. Copy the full license text from [`nbb-1.1.0-license.txt`](./nbb-1.1.0-license.txt) into a `LICENSE` file in your project root.
2. Add the license reference to your dataset metadata (e.g., in JSON headers) or documentation:

```json
{
  "license": "NBB 1.1.0",
  "license_url": "https://github.com/lev26548-pixel/nbb-license",
  "source": "https://your-project-link.com"
}
```
