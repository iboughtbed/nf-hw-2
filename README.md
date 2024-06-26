# [Blog](https://iboughtbed-nf-hw-2.vercel.app/)

This is an open source todo app build with everything new in Next.js 14. It is bootstrapped with `create-t3-app`.

[![Blog](./public/og.png)](https://iboughtbed-nf-hw-2.vercel.app/)

## Tech Stack

- **Framework:** [Next.js](https://nextjs.org)
- **Styling:** [Tailwind CSS](https://tailwindcss.com)
- **UI Components:** [shadcn/ui](https://ui.shadcn.com)
- **State management** [Jotai](https://jotai.org)

## Features to be implemented

- [x] Components for tasks (TaskList, TaskItem)
- [x] Add, complete or delete tasks
- [x] Save tasks to LocalStorage
- [x] Use an atomic approach via Jotai atoms with storage

## Running Locally

1. Clone the repository

   ```bash
   git clone https://github.com/iboughtbed/nf-hw-2.git
   ```

2. Install dependencies using pnpm

   ```bash
   pnpm install
   ```

3. Copy the `.env.example` to `.env` and update the variables.

   ```bash
   cp .env.example .env
   ```

4. Start the development server

   ```bash
   pnpm run dev
   ```

## Introduction

This is nFactorial Incubator homework for day 2

## License

Licensed under the MIT License. Check the [LICENSE](./LICENSE.md) file for details.
