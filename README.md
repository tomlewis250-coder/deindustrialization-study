# The True Cost of Deindustrialization

A comprehensive county-level analysis of how manufacturing job losses affected wages, employment, and economic wellbeing across America.

## Live Preview

Open `index.html` in any web browser to view the site locally.

## Free Hosting Options

### Option 1: GitHub Pages (Recommended)

1. **Create a GitHub account** at https://github.com if you don't have one

2. **Create a new repository**
   - Go to https://github.com/new
   - Name it something like `deindustrialization-analysis`
   - Make it **Public**
   - Click "Create repository"

3. **Upload your files**
   - Click "uploading an existing file"
   - Drag and drop ALL files from this `website` folder:
     - `index.html`
     - `images/` folder (with all PNGs)
   - Click "Commit changes"

4. **Enable GitHub Pages**
   - Go to repository Settings > Pages
   - Under "Source", select "main" branch
   - Click Save
   - Your site will be live at: `https://yourusername.github.io/deindustrialization-analysis/`

### Option 2: Netlify (Easiest)

1. Go to https://app.netlify.com/drop
2. Drag and drop the entire `website` folder
3. Done! You'll get a URL like `random-name.netlify.app`
4. You can customize the URL in settings

### Option 3: Vercel

1. Go to https://vercel.com and sign up
2. Click "New Project" > "Import Git Repository" or upload folder
3. Your site deploys automatically

## File Structure

```
website/
├── index.html          # Main webpage
├── images/             # All chart images
│   ├── 01_mfg_change_distribution.png
│   ├── 01_wage_premium_analysis.png
│   ├── 02_category_comparison.png
│   ├── 02_industry_replacement.png
│   ├── 03_labor_force_participation.png
│   ├── 03_scatter_mfg_vs_employment.png
│   ├── 04_economic_distress.png
│   ├── 04_mfg_employment_time_series.png
│   ├── 05_state_analysis.png
│   ├── 05_top_losing_counties.png
│   ├── 06_emp_change_by_category.png
│   ├── 06_the_complete_story.png
│   └── 07_state_mfg_change.png
├── css/                # (empty - styles are inline)
├── data/               # (empty - for future data files)
└── README.md           # This file
```

## Data Sources

- **BLS QCEW**: Bureau of Labor Statistics Quarterly Census of Employment and Wages (2000-2023)
- **Census ACS**: American Community Survey 5-year estimates (2010-2022)

## Key Findings

- **4.6 million** manufacturing jobs lost since 2000
- **$743/week** wage gap between manufacturing and replacement industries
- **-6.3 percentage points** lower labor force participation in severely affected counties
- **+5.1 percentage points** higher poverty in deindustrialized counties

## Customization

To customize the site:
- Edit `index.html` in any text editor
- Change colors by modifying the CSS variables at the top of the `<style>` section
- Add your name/organization in the footer
- Add a custom domain via your hosting provider

## Contact

Analysis by [Your Name]
