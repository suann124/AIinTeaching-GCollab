# PID Control - Static Webpage with Google Colab Integration

This prototype demonstrates a **static lecture webpage** linked to an **interactive Google Colab notebook** for hands-on PID control learning.

## 🎯 Concept

- **Static HTML**: Clean, fast-loading lecture content from `pid_manual.md`
- **Interactive Lab**: All code experiments and visualizations in Google Colab
- **Seamless Integration**: Direct links from theory to practice

## 📁 Files

- `index.html` - Main static webpage with PID theory
- `styles.css` - Modern, responsive styling
- `PID_Interactive_Lab.ipynb` - Complete interactive notebook
- `README.md` - This file

## 🚀 Setup Instructions

### Step 1: Upload Notebook to Google Colab

1. Go to [Google Colab](https://colab.research.google.com/)
2. Upload `PID_Interactive_Lab.ipynb`
3. **Make it shareable**:
   - Click "Share" button
   - Set to "Anyone with the link can view"
   - Copy the sharing URL

### Step 2: Update HTML Links

Edit `index.html` and replace `YOUR_NOTEBOOK_ID_HERE` with your actual Colab URL:

```javascript
// In index.html, line ~200
const COLAB_NOTEBOOK_URL = "https://colab.research.google.com/drive/YOUR_ACTUAL_NOTEBOOK_ID";
```

### Step 3: Deploy Static Site

**Option A: GitHub Pages**
1. Create new repository
2. Upload `index.html`, `styles.css`, `README.md`
3. Enable GitHub Pages in repository settings
4. Your site will be available at `https://yourusername.github.io/repo-name`

**Option B: Local Testing**
1. Open `index.html` in any web browser
2. Test all navigation and Colab links

**Option C: Other Hosting**
- Netlify: Drag and drop the files
- Vercel: Connect to GitHub repository
- GitHub Codespaces: Use built-in web server

## 🔗 Workflow

1. **Student visits static webpage** - Fast loading, clean theory presentation
2. **Clicks "Open in Colab"** - Launches interactive notebook in new tab
3. **Runs experiments** - Live code execution, visualizations, hands-on learning
4. **Returns to theory** - Seamless integration between static and interactive content

## ✨ Key Features

### Static Webpage
- ✅ Clean, distraction-free reading experience
- ✅ Mathematical equations rendered with MathJax
- ✅ Responsive design for all devices
- ✅ Fast loading (no heavy JavaScript frameworks)
- ✅ Print-friendly styles
- ✅ Interactive exercise callouts with direct Colab links

### Google Colab Notebook
- ✅ All interactive code from the original Jupyter Book
- ✅ Step-by-step PID experiments
- ✅ Real-time plotting and visualization
- ✅ Complete discrete PID implementation
- ✅ Performance analysis tools
- ✅ Troubleshooting examples

## 📊 Comparison with Original Jupyter Book

| Feature | Original Jupyter Book | This Prototype |
|---------|----------------------|----------------|
| **Loading Speed** | Slower (full book build) | ⚡ Instant (static HTML) |
| **Offline Access** | ❌ Needs build process | ✅ Works offline |
| **Mobile Experience** | Good | ✅ Optimized responsive design |
| **Code Execution** | Thebe (browser-based) | 🚀 Google Colab (cloud-based) |
| **Sharing** | Complex (book deployment) | ✅ Simple (static URL + Colab link) |
| **Maintenance** | High (build system) | ✅ Low (static files) |

## 🎓 Educational Benefits

1. **Separation of Concerns**:
   - Theory reading without distractions
   - Focused coding environment in Colab

2. **Better Performance**:
   - Static page loads instantly
   - Colab handles computation without browser limitations

3. **Easier Sharing**:
   - Simple URL for theory
   - Standard Colab sharing for notebooks

4. **Device Flexibility**:
   - Read theory on any device
   - Code on devices with better computational resources

## 🔧 Customization

### Adding More Sections
1. Add new `<section>` to `index.html`
2. Add corresponding cells to Colab notebook
3. Update navigation links

### Styling Changes
1. Modify `styles.css`
2. Use CSS custom properties for easy theme changes
3. All styles are responsive and print-friendly

### Colab Notebook Extensions
1. Add new cells to `PID_Interactive_Lab.ipynb`
2. Use section headers for easy navigation
3. Include performance metrics and visualizations

## 🌟 Next Steps

- [ ] Create additional static pages for other control topics
- [ ] Add more advanced PID experiments to Colab
- [ ] Implement dark mode toggle
- [ ] Add PDF export functionality
- [ ] Create template for other subjects

## 📝 License

This educational content is available for academic use. Please cite appropriately if used in research or teaching.

---

**Built for effective PID control education! 🎛️**