# Figma Skill

## Figme Shortcut
| Action                         | Mac Shortcut          |       
|--------------------------------|------------------------|
| **Frame Tool**                 | `F`                    | 
| **Move Tool**                  | `V`                    | 
| **Scale Tool**                 | `K`                    |
| **Rectangle Tool**             | `R`                    | 
| **Text Tool**                  | `T`                    | 
| **Pen Tool**                   | `P`                    | 
| **Hand Tool** (Pan)            | `Space`                | 
| **Zoom Tool**                  | `Z`                    | 
| **Group Selection**            | `⌘ + G`                | 
| **Ungroup**                    | `⌘ + Shift + G`        | 
| **Copy**                       | `⌘ + C`                | 
| **Paste**                      | `⌘ + V`                | 
| **Duplicate**                  | `⌘ + D`                | 
| **Send to Back / Front**       | `⌘ + [` / `⌘ + ]`      | 
| **Align Left / Right / Center**| `⌥ + A/L/R/C`          | 
| **Zoom to Fit**                | `Shift + 1`            | 
| **Toggle UI**                  | `⌘ + \``               | 
| **Quick Actions (Search)**     | `⌘ + /`                | 
| **Open a file**                | `Shift + ⌘ + K`        | 
| **Auto Layout**                | `Shift + A`            | 
| **Making a general frame**     | `⌥ + ⌘ + G`            | 
| **Hide tool**                  | `⌘ + \`                | 
| **Hide grid**                  | `Shift + G`            | 

**AI-Specific Workflow Tips**

| Task                        | Shortcut or Plugin Usage         |
|-----------------------------|----------------------------------|
| Launch Figma AI prompt UI   | Use plugin (e.g. **Magician**)   |
| Launch MCP context editor   | `Right-click → MCP`              |
| Quick layout generation     | Use `Cmd/Ctrl + /` to search plugins like “Diagram AI” |
| Generate UX copy            | Use AI plugins like **Jasper** or **Magician** |
| Simulate AI interactions    | Install and configure **Figma MCP** plugin |

**Pro Tip**:
Use `⌘ + /` to **quick-launch plugins, layers, assets**, and AI tools in seconds!

---

## The Basics of Figma

<details>
  <summary>Toolbar</summary>

**Scale tool** - Using the scale tool can streamline your design process and ensure that your components maintain their visual balance as you adjust their size.

**Frames tool** - Frames are essentially containers that act as the building blocks for your layouts. They can function like artboards or components, grouping elements together.

**Section tool** - Sections are used primarily for organizing and structuring your Figma files, especially when working on large projects. They act as visual dividers or containers that group multiple frames or elements.

**Slice tool** - The slice tool in Figma lets you define specific areas of your design for export without affecting the overall layout. It’s particularly useful when you need to extract assets or parts of a design that aren’t neatly contained in a frame or group.
</details>

<details>
  <summary>Right sidebar</summary>
  

<details>
  <summary>Design</summary>
    
### Container
- **Frame** - Best for building and controlling layouts with detailed design and interaction properties.
- **Group** - Group are a geat way to combine layers into a single element. Ideal for simple, temporary organization without the need for advanced layout features.
- **Section** - Perfect for organizing your overall workspace, helping you manage and navigate large projects.

### Components
Components in Figma are reusable design elements that help you maintain consistency, speed up your workflow, and build scalable design systems. 

### Auto Layout vs. Constraints
In auto layout frames, the auto layout settings primarily manage the arrangement of elements. For items placed inside an auto layout frame, the auto layout rules will often take precedence, which might make traditional constraints less noticeable. But in static frames or nested scenarios outside of auto layout, constraints remain very useful for pinning elements to specific positions.
- Auto layout(responsive layout) - When you want to streamline the creation of responsive components and interfaces that need to adapt to varying content sizes automatically.
- Constraints - Constraints allow you to define how elements should behave when their parent frame changes size—pinning them to the top, bottom, left, right, or center. This feature is still essential for responsive design, particularly when you’re not using auto layout. When you need precise control over individual element placement, especially in static designs or when building responsive designs manually.

### Creating style(defined your style)
- Text style
- Color style
- Fill style(images background)
- Effect
- layout Grid 

### Image
- Masks on a image

###Form
</details>  

    
<details>
  <summary>Prototyping</summary>

- Flows and Starting Points
- Interravtions
- Scroll behavior
</details>  
</details>


<details>
  <summary>Setting up page widths in Figma</summary>

### Setting up page widths in Figma
- **Website (Desktop)Recommended width: 1440px**
    - **Safe content area: 1280px or 1140px** (max width for readable content)
    - **Grid system**: Use 12 columns, 1140px max width, 20–30px gutters
    - 1920px (Full HD, for large screens)
    - 1280px (Smaller laptops)
    - 1024px (Tablet landscape breakpoints)
- Web App **(Dashboard UI) Common design canvas width: 1440px or 1600px**
    - Content area: Often constrained to around 1200px–1280px 

    | Device Type       | Width Range (px) | Notes                                  |
    |-------------------|------------------|----------------------------------------|
    | Mobile (Portrait) | 320–480          | Use 375px as standard reference width  |
    | Mobile (Landscape)| 480–768          | Use 568px or 667px for wider mobiles   |
    | Tablet            | 768–1024         | Use 768px or 834px as base             |
    | Laptop            | 1024–1440        | Use 1280px or 1366px for common layouts|
    | Desktop           | 1440–1920+       | 1440px is industry standard baseline   |

- Tips for Figma Setup
    - Use "Frame" instead of "Artboard" and select a desktop preset like “**Desktop 1440**” or custom dimensions.
    - Apply a grid system (**12 column**) to align content.
    - Keep margins of **at least 16px–24px** on mobile, 60px–120px on desktop.
</details>

## Figma Dev Mode
Dev Mode built for developers and gives you the power **to easily inspect designs and translate them into code**—without changing the design file. 
- [Figma Dev Mode](https://www.figma.com/dev-mode/)

### Figma MCP

Unlock design-informed code generation through MCP


<details>
  <summary>What is Figma MCP?</summary>

Figma MCP refers to Figma's Dev Mode MCP server, which brings Figma directly into the developer workflow to help LLMs **achieve design-informed code generation**.

### What is MCP?
MCP stands for Model Context Protocol, a standard for how applications provide context to LLMs. It's an open source standard for how AI-powered systems can connect to software applications, tools, and platforms.

### Figma's Dev Mode MCP Server
The Dev Mode MCP server allows developers to bring context from Figma into agentic coding tools like Copilot in VS Code, Cursor, Windsurf, and Claude Code. Instead of just feeding screenshots to AI tools, this server provides structured design data directly from Figma's API.

### Key Benefits:

- **Design-to-Code Workflows**: Whether it's creating new atomic components with the proper variables and stylings or building out multi-layer application flows, **the server provides a more efficient and accurate design-to-code workflow**.
- **Better Context**: By providing references to specific variables, components, and styles, the Dev Mode MCP server can make generated code more precise, efficient, and reduce LLM token usage.
- **Direct API Access**: Instead of AI tools guessing from screenshots, they get actual design data including components, styles, and layout information

### Current Status
The Dev Mode MCP Server is currently in open beta Guide to the Dev Mode MCP Server – Figma Learn - Help Center and works with various AI coding tools. You can only use the Dev Mode MCP server from the Figma desktop app.

This represents a significant improvement over traditional design handoff processes, allowing AI coding assistants to understand design intent more accurately by accessing structured design data rather than just visual information.RetryClaude can make mistakes. Please double-check cited sources.
</details>


<details>
  <summary>Figma MCP Setup Guide</summary>
> **Note**: The Figma Dev Mode MCP Server is currently in **open beta**. Some functions and settings may not yet be available, and you may experience bugs or performance issues during the beta period.

## What is Figma MCP?

Figma MCP (Model Context Protocol) is a server that brings Figma directly into your developer workflow, enabling AI coding tools to access structured design data for more accurate design-to-code generation. Instead of relying on screenshots, AI tools can now access components, variables, styles, and layout information directly from Figma's API.

## Prerequisites

### Required
- **Figma Account**: Professional, Organization, or Enterprise plan with Dev or Full seat
- **Figma Desktop App**: MCP server only works with the desktop app (not web version)
- **Compatible AI Coding Tool**: VS Code with GitHub Copilot, Cursor, Windsurf, or Claude Code
- **Figma API Token**: Personal access token with read permissions

### System Requirements
- Node.js and npm installed
- Compatible operating system (Windows, macOS, or Linux)

## Step 1: Install Figma Desktop App

1. Visit [Figma's official website](https://www.figma.com)
2. Download the desktop app for your operating system
3. Install and log in with your Figma credentials

## Step 2: Generate Figma API Access Token

1. **Open Figma Account Settings**:
   - Click your profile icon in Figma
   - Select "Settings" from the dropdown

2. **Navigate to Security Tab**:
   - Go to the "Security" section in settings

3. **Create Personal Access Token**:
   - Click "Create new personal access token"
   - Name your token (e.g., "Figma_MCP")
   - Click "Create"

4. **Save Your Token**:
   - **Important**: Copy the token immediately - Figma only shows it once
   - Store it securely (password manager recommended)
   - Never hardcode the token in your codebase

## Step 3: Choose Your Setup Method

### Option A: Official Figma Dev Mode MCP Server (Recommended)

The official server is built into Figma's desktop app and requires no additional installation.

**Supported Tools:**
- VS Code with GitHub Copilot
- Cursor
- Windsurf
- Claude Code

### Option B: Community MCP Servers

Several community-built servers are available for different use cases:

#### Quick NPM Installation
```bash
# Run directly without installation
npx figma-developer-mcp --figma-api-key=YOUR_API_KEY

# Alternative package managers
pnpx figma-developer-mcp --figma-api-key=YOUR_API_KEY
yarn dlx figma-developer-mcp --figma-api-key=YOUR_API_KEY
bunx figma-developer-mcp --figma-api-key=YOUR_API_KEY
```

## Step 4: Configure Your AI Coding Tool

### VS Code Setup

1. **Prerequisites**: Ensure GitHub Copilot is enabled on your account
2. **Enable MCP**: The official Figma MCP server should automatically appear in VS Code
3. **Verify Installation**: Look for available tools in your VS Code interface
4. **Restart if needed**: Restart both Figma desktop app and VS Code if tools don't appear

### Cursor Setup

1. **Open Settings**: Go to Cursor → Settings → Cursor Settings
2. **Navigate to MCP**: Click on the "MCP" tab
3. **Add Server**: Click "+ Add new global MCP server"
4. **Configure**: Add the Figma MCP server configuration
5. **Restart**: Restart Cursor to apply changes

**Configuration Example:**
```json
{
  "mcpServers": {
    "Figma MCP": {
      "command": "npx",
      "args": ["-y", "figma-developer-mcp", "--figma-api-key=YOUR_API_KEY", "--stdio"]
    }
  }
}
```

### Windsurf Setup

1. **Open Settings**: Windsurf → Settings → Windsurf Settings (or ⌘ ,)
2. **Plugin Store**: Navigate to Cascade settings → Open plugin store
3. **Install Plugin**: Search for "Figma" and install the plugin
4. **Verify**: Open Cascade - you should see the Figma MCP server and tools

**Note**: For Windsurf, change the `url` property to `serverUrl` in configuration files.

### Claude Code Setup

1. **Desktop Settings**: Open Claude menu → Settings (not in-app settings)
2. **Developer Section**: Click "Developer" → "Edit Config"
3. **Edit Config**: Open `claude_desktop_config.json` and add configuration
4. **Restart**: Restart Claude desktop app
5. **Verify**: Look for hammer icon in bottom right of input box

**Configuration Example:**
```json
{
  "mcpServers": {
    "figma-mcp": {
      "command": "npx",
      "args": ["figma-mcp"],
      "env": {
        "FIGMA_API_KEY": "YOUR_API_KEY"
      }
    }
  }
}
```

## Step 5: Test Your Setup

1. **Copy Figma URL**: In Figma, copy the link to a frame or layer
2. **Prompt Your AI Tool**: Ask it to implement the design at the copied URL
3. **Verify Context**: The AI should access structured design data, not just visual information

**Example Prompt:**
```
"Help me implement the design at this Figma URL: [paste your Figma link here]"
```

## Best Practices for Better Results

### Design Preparation
- **Use Components**: Create components for reusable elements (buttons, cards, inputs)
- **Link to Code**: Use Code Connect to link components to your codebase
- **Test Responsiveness**: Resize frames to ensure expected behavior
- **Add Annotations**: Use dev resources to convey design intent

### Effective Prompting
- **Be Specific**: Align results with your framework or styling system
- **Target Paths**: Specify where to add code (e.g., `src/components/ui`)
- **Layout Systems**: Specify preferred layout approach (grid, flexbox, absolute)
- **Modify vs Create**: Ask to modify existing files instead of creating new ones

**Good Prompt Example:**
```
"Implement this Figma design using React and Tailwind CSS, add it to src/components/ui, and use flexbox for layout"
```

### Context Optimization
- **Provide Design Context**: The more structured data available, the better
- **Use Design Systems**: Maintain consistency with established patterns
- **Configure Settings**: Adjust MCP server settings based on your needs

## Troubleshooting

### Common Issues

**MCP Server Not Appearing:**
- Restart Figma desktop app and your coding tool
- Verify API token is correct and has proper permissions
- Check that you're using the desktop app, not web version

**Poor Code Generation:**
- Ensure components are properly structured in Figma
- Add clear annotations for complex interactions
- Use specific prompts with framework details

**Token Issues:**
- Generate a new token if the current one isn't working
- Verify token has read permissions
- Store token securely and avoid hardcoding

### Getting Help

- **Official Documentation**: Check Figma's Help Center for latest updates
- **Community Support**: Join Figma community forums
- **Beta Feedback**: Use Figma's feedback form for beta-specific issues

## Security Notes

- **Token Safety**: Never commit API tokens to version control
- **Revoke Compromised Tokens**: Immediately revoke and regenerate if token is compromised
- **Environment Variables**: Use environment variables for token storage
- **Team Access**: Configure appropriate permissions for team usage

## Current Limitations

- **Beta Status**: Features may be incomplete or unstable
- **Desktop Only**: Web version of Figma not supported
- **Component Issues**: Some community servers have trouble with Figma components vs plain frames
- **Responsive Design**: Mobile responsiveness may not be perfectly implemented
- **Non-Deterministic**: AI interpretation can vary between generations

## What's Next?

The Figma MCP ecosystem is rapidly evolving. Stay updated with:
- Official Figma announcements
- Community-developed servers and plugins
- Integration improvements with AI coding tools
- Enhanced design-to-code workflows

---

**Last Updated**: June 2025  
**Status**: Open Beta  
**Official Documentation**: [Figma Help Center](https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Dev-Mode-MCP-Server)
</details>

### Figma AI plugins

<details>
  <summary>Figma AI Plugins Guide</summary>

## What are Figma AI Plugins?

Figma provides a set of AI plugins that can be used to generate content and design elements. These plugins are available in the Figma Community. AI plugins harness artificial intelligence and machine learning to automate repetitive design tasks, generate content, enhance creativity, and streamline workflows within Figma.

From automating repetitive tasks to generating complex design elements, these tools are designed to help you work smarter, not harder.

## Key Benefits of Figma AI Plugins

- **Automation**: Reduce time spent on repetitive tasks like layer naming, content generation, and asset creation
- **Enhanced Creativity**: Generate unique design elements, color palettes, and visual assets with AI assistance
- **Improved Workflows**: Streamline design-to-code processes and team collaboration
- **Content Generation**: Create realistic text, images, and mockups without external resources
- **Accessibility**: Improve design accessibility with automated checks and suggestions

## Categories of Figma AI Plugins

### 1. Design Generation & Automation

#### **Banani** - AI Design Copilot
Banani is a design copilot for Figma. It can generate app UI designs from a simple text description with AI. You can use those mockups as a solid starting point and save tone of time.

**Features:**
- Generate complete UI designs from text descriptions
- Mix components and themes from different apps
- Create app mockups in minutes
- Support for multiple design patterns

#### **Musho** - AI Website Generator
</details>