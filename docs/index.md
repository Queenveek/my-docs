# Welcome to My Documentation

This is my documentation homepage.

## Features

- Easy to use
- Mobile friendly
- Automatically updates

## Getting Started

Start reading the documentation by exploring

# This is a heading (biggest)
## This is a smaller heading
### Even smaller heading

**This text is bold**
*This text is italic*

- Bullet point 1
- Bullet point 2
- Bullet point 3

1. Numbered item 1
2. Numbered item 2

[This is a link](https://example.com)

`This is code`

```python
# This is a code block
print("Hello")
**What happens:**
- MkDocs converts your Markdown to HTML (web page)
- `# Welcome` becomes `<h1>Welcome</h1>` in HTML
- The HTML is what you see in your browser

**File behavior:**
- You can edit this directly on GitHub
- Every time you save (commit), Read the Docs rebuilds
- Changes appear on your website in 1-2 minutes

---

### 5. **`about.md`** (About Page Content)

**What it is:**
- Another Markdown file
- The content of your "About" page
- Works exactly like `index.md`

**Why separate files:**
- Each page = one `.md` file
- Keeps content organized
- Easy to find and edit specific pages

**Naming convention:**
- Filename should match what it is: `about.md`, `installation.md`, `api-reference.md`
- Use lowercase and hyphens (not spaces)
- ✅ `getting-started.md`
- ❌ `Getting Started.md`
- ❌ `getting_started.md`

---

### 6. **`docs/`** (Folder)

**What it is:**
- A folder (directory) that contains all your Markdown files
- Standard MkDocs structure

**Why a folder:**
- Separates documentation content from configuration files
- Keeps things organized
- MkDocs expects all content to be in `docs/` by default

**Structure:**
my-docs/
├── .readthedocs.yaml    (Read the Docs config)
├── mkdocs.yml           (MkDocs config)
├── requirements.txt     (Python packages)
└── docs/                (Content folder)
├── index.md         (Homepage)
├── about.md         (About page)
├── tutorial.md      (Tutorial page)
└── images/          (Subfolder for images)
└── logo.png
---

### 7. **`README.md`** (Repository Description)

**What it is:**
- Special file that GitHub displays on your repository homepage
- NOT part of your documentation website
- Just describes your project on GitHub

**Where you see it:**
- Go to `github.com/yourusername/my-docs`
- The README content appears below the file list

**Purpose:**
- Tell visitors what your repository is about
- Give instructions on how to use or contribute
- Standard for all GitHub projects

---

## FILE EXTENSIONS EXPLAINED

### **`.yml` or `.yaml`**
- **Format:** YAML (configuration files)
- **Used for:** Settings, structure, configuration
- **Sensitive to:** Spaces and indentation (2 spaces = one level)
- **Example files:** `.readthedocs.yaml`, `mkdocs.yml`, `docker-compose.yml`

**YAML rules:**
```yaml
# This is correct:
key: value
parent:
  child: value
  another_child: value

# This is WRONG (bad indentation):
key: value
parent:
child: value
