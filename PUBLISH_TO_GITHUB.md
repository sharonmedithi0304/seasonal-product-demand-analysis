# Publish this project to GitHub

The project files are prepared, but this bundle has **not** been pushed to GitHub yet.

## 1. Create the repository

On GitHub, create a repository named `seasonal-product-demand-analysis` under `sharonmedithi0304`. Choose **Public** if you want to use it in your portfolio. Do not initialize it with a README, `.gitignore`, or license because those files are already included here.

## 2. Upload with Git (Windows)

Extract `Seasonal_Product_Demand_Analysis_GitHub.zip`, open Command Prompt or PowerShell in the extracted `Seasonal_Product_Demand_Analysis_GitHub` folder, and run:

```bash
git init -b main
git add .
git commit -m "Prepare seasonal product demand analysis"
git remote add origin https://github.com/sharonmedithi0304/seasonal-product-demand-analysis.git
git push -u origin main
```

If GitHub asks you to authenticate, complete the browser sign-in flow. Do not paste access tokens into the notebook or README.

## 3. Verify the published page

Open the repository page and check that:

- the README displays the charts;
- the notebook is under `notebooks/`;
- the CSV summaries and figures appear under `outputs/`;
- the raw Excel workbook is **not** uploaded (it is excluded by `.gitignore`).

The README's Colab badge and clone commands target the repository name above. If you choose a different owner or name, update those links.
