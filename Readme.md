# ResearchLens: AI Research Intelligence Platform

A web-based prototype that helps you understand research papers faster. Upload a PDF and ResearchLens reads it in your browser, organises it section by section, answers questions about it, compares papers and generates editable reports.

## Features
- Login and signup (local, no external accounts)
- Dashboard with papers, reports and activity
- PDF upload and paper library
- Paper analysis: abstract, methods, results, limitations, future work and more
- Chatbot that answers from the paper with page references
- Side-by-side paper comparison
- Research gap explorer
- Report and literature review generator (edit and download)

## Notes
- Runs fully in the browser from a single `index.html`. No server, no API keys, no paid services.
- Your papers and reports are saved locally in the browser (IndexedDB), so data stays on your device.
- If information is missing from a paper, it says "Not available" instead of inventing it.



Built with HTML, CSS, JavaScript and pdf.js.