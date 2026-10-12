# DecisionCheck

Interactive classroom prototype for behavioral finance in acquisition reviews.

## Publish through GitHub Pages

1. Unzip this download.
2. Create a public GitHub repository, such as `decisioncheck`.
3. Choose **Add file → Upload files**. Upload the contents of the extracted folder directly to the repository root, then commit them. Upload the individual files, not the ZIP itself or a containing folder.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch **main** and folder **/(root)**, then click **Save**.
7. Wait for the deployment. The Pages settings will provide your published URL, typically `https://YOUR-USERNAME.github.io/decisioncheck/`.

The entry file must be named `index.html` and sit at the root of the publishing source. No package installation, build command, secret or backend is needed.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Files

- `index.html`: application layout, content and research links.
- `style.css`: responsive design and orange theme.
- `app.js`: forecasts, calculations, review stages and printable decision packet.
- `.nojekyll`: serves the static files without Jekyll processing.

## Try the demo

Open `index.html` in a modern browser, or visit the deployed site. Submit the independent forecast, compare assumptions, record premortem concerns, then generate the committee packet. Print the packet to save it as a PDF.

## Scope and data behavior

All deal numbers and benchmarks are fictional. The product capabilities are proposed. The prototype does not diagnose bias or establish product effectiveness.

Each visitor has a separate in-memory review. Entries stay in that browser tab and disappear after refresh or reset. There are no accounts, shared submissions, uploads, database or AI service. The private-submission sequence is illustrative and does not provide secure multi-user forecast collection.

Google Fonts is used for optional typography. System fonts provide a fallback.

## Calculation

Incremental NPV = $90M standalone target value + PV of synergy cash flows − upfront integration cost − $100M purchase price. The discount rate is 10%. Synergy cash flows begin at the end of the selected year and continue through year 5, with no synergy terminal value.

The sponsor case uses $12M annually in years 1–5 and $4M integration cost, giving $31.49M NPV. The prefilled reviewer case uses $6M annually in years 2–5 and $9M integration cost, giving −$1.71M NPV.

## Attribution

ChatGPT assisted with concept development and implementation. Research sources appear in the site's About dialog. No external credentials or ChatGPT hosting configuration are included in this package.
