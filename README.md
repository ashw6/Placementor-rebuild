# Placementor

Placementor is a multi-page placement preparation website for students. It includes mock interviews with structured feedback, a resume builder and local resume scanner, company preparation guides, example role listings, aptitude and coding practice, and a saved placement roadmap.

## Run it

1. Install Node.js if it is not already installed.
2. Open a terminal in this folder.
3. Run `npm start` (or `node server.js`).
4. Open <http://localhost:4173>.

It uses Node's built-in web server and has no packages to install. Profile details, practice scores, resume drafts, and roadmap progress are saved in the browser on this device.

## Optional AI coaching

The site works without an AI provider key and gives local, rules-based coaching feedback. To enable extra OpenAI feedback:

1. Copy `.env.example` to `.env`.
2. Add your OpenAI API key to `OPENAI_API_KEY` and choose a model in `OPENAI_MODEL`.
3. Restart the server.
4. In the interview or resume scanner, select the opt-in checkbox before requesting feedback.

The key stays on the server. A resume or interview answer is sent to OpenAI only after the student selects the matching opt-in. API usage may incur charges.

## Demo content

Company guides describe common preparation themes and example hiring stages. Job cards are sample role paths, not current vacancies. Confirm live roles and current requirements on the employers' career pages.
