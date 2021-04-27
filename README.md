# 快速开始一个基础Typescript的React项目 创建基于 Typescript 的应用

  React 默认是使用 yarn 进行包管理   npx create-react-app todolist-ts --template typescript.\
  使用npm进行包管理 npx create-react-app todolist-ts --template typescript --use-npm

# 安装依赖库 
1：进入你的项目 [cd todolist-ts].\
2：执行以下命令.\
    yarn add redux react-redux @types/react-redux -S.\
    或 .\
    npm add redux react-redux @types/react-redux -S

## Available Scripts 

在项目目录中，可以运行：
In the project directory, you can run: 

### `npm start`
在开发模式下运行应用程序。.\
打开[http://localhost:3000](http://localhost:3000)在浏览器中查看它。

如果您进行编辑，则页面将重新加载。.\
您还将在控制台中看到任何棉绒错误。
Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

在交互式监视模式下启动测试运行器。.\
有关更多信息，请参见关于[运行测试](https://facebook.github.io/create-react-app/docs/running-tests)的部分。

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

生成用于生产的应用程序到build文件夹。.\
它在生产模式下正确捆绑了React，并优化了构建以获得最佳性能。

生成被最小化，并且文件名包括哈希值。.\
您的应用已准备好进行部署！

有关更多信息，请参见关于[部署](https://facebook.github.io/create-react-app/docs/deployment)的部分。

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**注意：这是单向操作。一旦您eject，您将无法返回！**
**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

如果您对构建工具和配置选择不满意，则可以eject随时进行。此命令将从您的项目中删除单个生成依赖项。

相反，它将所有配置文件和传递依赖项（webpack，Babel，ESLint等）直接复制到您的项目中，因此您可以完全控制它们。除了这些命令以外的所有命令eject仍然可以使用，但是它们将指向复制的脚本，因此您可以对其进行调整。在这一点上，您是一个人。

您无需使用eject。精选的功能集适用于中小型部署，您不应该使用此功能。但是，我们了解到，如果在准备就绪时无法自定义该工具，它将不会有用。

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More 学到更多

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
