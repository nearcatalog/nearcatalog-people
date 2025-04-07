# NEARCatalog - People on NEAR

A community-maintained directory of individuals and teams building on the NEAR ecosystem. This repository is part of the [NEARCatalog](https://nearcatalog.xyz) project, which aims to showcase the vibrant NEAR ecosystem.

## About

This repository contains a curated list of people actively involved in the NEAR ecosystem, including foundation members, developers, community leaders, and contributors. The data is stored in a single JSON file (`people-on-near.json`) that can be easily updated through GitHub's collaborative workflow.

This is dev-oriented repo, for normal users, you can submit your request here instead:  

## View the Directory

Visit [NEARCatalog](https://nearcatalog.xyz/people) to view the compiled directory of people building on NEAR.

## Structure

Each person in the directory is represented by a JSON object with the following structure:

```json
{
  "name": "Full Name",                          // Required
  "preferredContact": "Telegram",               // Required: "Email", "Telegram", "X", etc.
  "description": "Short bio or description, something like what do you do, reason to contact you...",    // Required
  "organization": "Organization Name",          // Optional
  "team": "Team Name",                          // Optional
  "jobTitle": "Job Title",                      // Optional
  "email": "email@example.com",                 // Optional
  "telegram": "https://t.me/username",          // Optional
  "twitter": "https://x.com/username",          // Optional
  "website" : "https://example.com", 			// Optional
  "avatar": "https://example.com/avatar.jpg"   // Optional: URL to profile image
}
```

## How to Contribute

### Adding or Updating Your Information

1. **Fork this repository** by clicking the "Fork" button in the top right corner.

2. **Clone your forked repository** 

3. **Edit the people-on-near.json file** to add or update your information:
   - If adding yourself, add a new JSON object at the end of the array
   - If updating your existing information, find and modify your entry

4. **Commit your changes**:

5. **Push to your fork**:
   ```bash
   git push
   ```

6. **Create a pull request** by navigating to your fork on GitHub and clicking "Contribute" > "Open pull request".

### Contribution Guidelines

- **Accuracy**: Provide accurate information that you're comfortable sharing publicly.
- **Appropriate Content**: Keep all information professional and appropriate.
- **Required Fields**: At minimum, include your name and preferred contact method.
- **Avatar Images**: If providing an avatar URL, ensure it's a stable link that won't change or expire.
- **Validation**: Ensure your JSON is properly formatted (you can use tools like [JSONLint](https://jsonlint.com/)).

## FAQs

**Q: Can I add my organization or team members?**  
A: Yes, you can add multiple entries for your team members, but please make sure they consent to being listed.

**Q: How do I remove my information?**  
A: Submit a pull request that removes your entry from the JSON file, or open an issue requesting removal.

**Q: What is NEARCatalog?**  
A: [NEARCatalog](https://nearcatalog.xyz) is an initiative to catalog and showcase projects, people, and resources in the NEAR ecosystem.

---

Maintained with ❤️ by the NEAR community