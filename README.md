# Welcome

## Mono Repo

- how to use

  - dev

    ```shell
    npm run dev
    ```

  - build

    ```shell
    npm run build
    ```

- deps installation

  - how to install deps for all projects

    ```shell
    npm install package-name -ws
    ```

  - how to install deps for specific project

    ```shell
    npm install package-name -w=@ma/project-name
    ```

  - how to install deps at root level

    ```shell
    npm install package-name -W
    ```

## Folder Structure

- print the folder structure

  - command # 🖥️ `mac`

    - `tree -L 3 -I node_modules`

  ```shell
  .
  ├── README.md
  ├── docs
  ├── domains
  │   └── finance
  │       ├── finance-admin-react
  │       └── finance-admin-vue3
  ├── package-lock.json
  ├── package.json
  └── packages
  ```

- how it is organized

  - by domain

    - by solution tech stack
      - by domain scene / story

  - by documentation
  - by shared packages
