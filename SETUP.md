# VINIL P — GitHub Profile Setup

## 1. Profile repository

Create/use the repository:

`Vinil-Official/Vinil-Official`

The repository must be public and the default branch should be `main`.

## 2. Add the README

Copy `README.md` from this package into the root of the profile repository.

## 3. Contribution snake

Copy:

`.github/workflows/snake.yml`

to:

`.github/workflows/snake.yml`

Then open the repository's:

**Settings → Actions → General → Workflow permissions**

Select **Read and write permissions**.

This is the **repository's** Actions setting, not the account-level setting.

Push to `main` and run the workflow manually once. The `output` branch is created by the workflow.

## 4. GitHub Readme Stats

The PDF's requested self-hosted setup is:

1. Create a GitHub classic Personal Access Token.
2. Use the `repo` scope.
3. Copy it immediately and never publish it.
4. Fork `anuraghazra/github-readme-stats`.
5. Import the fork into Vercel.
6. Add the Vercel environment variable:
   `PAT_1=<your token>`
7. Deploy.
8. Copy the Vercel deployment domain.
9. Replace `YOUR-VERCEL-INSTANCE.vercel.app` in `README.md`.

Do not put the PAT in this repository or in `README.md`.

## 5. Banner

The animated banner is intentionally not included yet because the required source photo and three logo references were not supplied.

Place the finished files here:

- `assets/banner-dark.svg`
- `assets/banner-light.svg`

Then uncomment the Phase 1 banner block in `README.md`.

## 6. Remaining placeholders

Replace:

- `YOUR_EMAIL@example.com`
- `YOUR_PORTFOLIO_URL`
- `YOUR-VERCEL-INSTANCE.vercel.app`

with your real values.

If you do not have a portfolio yet, use `coming soon` in your personal notes and remove the portfolio badge until the site exists.
