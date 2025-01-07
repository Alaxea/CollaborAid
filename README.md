# Collaboraid Project
A platform connecting non-governmental organizations (NGOs) with businesses, fostering their collaboration for a better future and enabling further growth.

To build and run follow these steps:

1. Install bun.sh

For windows:
`powershell -c "irm bun.sh/install.ps1 | iex"`

For Linux/MacOS:
`curl -fsSL https://bun.sh/install | bash`

2. Once you're at the root of repository run:
`bun install`

3. Start the database:
`bun src/back/manageDatabase.ts`

4. Open new terminal at the same location and run the following:
`bun run dev`

5. To open the page, hover your cursor over the "Local: http://..." link and press Ctrl while clicking on the link.
