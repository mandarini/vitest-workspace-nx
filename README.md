# Vitest workspace

[https://vitest.dev/guide/workspace.html](https://vitest.dev/guide/workspace.html)

In a Nx workspace, we are defining a [`vitest.workspace.ts`](vitest.workspace.ts) file with a glob to find all projects using `vitest` and run the corresponding tests when you run `npx vitest` in the workspace root.

Related issue: [https://github.com/nrwl/nx/issues/18204](https://github.com/nrwl/nx/issues/18204)
