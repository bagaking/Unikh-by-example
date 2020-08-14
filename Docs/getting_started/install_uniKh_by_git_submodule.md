# Install UniKh by git submoudle

使用 git 的 submodule 方式安装 UniKh 到你的 Unity 项目.

### Step 1

Create a git repository in the root of your project, or skip this step if the project is already managed by git.

在项目的根目录下建立 git 仓库, 如果该项目已经由 git 管理, 则可跳过这一步.

> `cd <PROJECT_ROOT_DIR>`
> `git init`

### Step 2

Run `git submodule add git@github.com:bagaking/UniKh.git . /Assets/UniKh` to create the submodule and set the path.

执行 `git submodule add git@github.com:bagaking/UniKh.git ./Assets/UniKh` 以建立 submodule 并设定路径.

If your git repository isn't set in the project's root directory, you'll need to tweak this command.

如果你的 git 仓库并非建立在根目录, 则需要适当调整这段命令.

### Step3

If the installation is succeeded, start your Unity project and then you will see the UniKh menu.

启动 Unity, 看到 UniKh 菜单即说明安装成功.
