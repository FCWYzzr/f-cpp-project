# f_cpp_project

## 项目介绍

这是一个使用C++23的项目框架，包含一个简单的示例以帮助快速上手。项目使用了现代C++特性，并通过CMake进行构建和测试。

## 设置

1. 克隆仓库：
   ```sh
   git clone --recurse-submodules https://github.com/FCWYzzr/f-cpp-project.git
   ```
2. 进入项目目录：
   ```sh
   cd f-cpp-project
   ```

## 项目结构

- `3rdparty`: 第三方库。
- `modules`: 项目的模块，包含源代码和测试文件。
   - `src/`: 源代码目录，包含主要的C++源文件和模块声明文件等。
   - `CMakeLists.txt`: 用于构建项目的CMake配置文件。

## 构建项目

推荐使用CLion + MSVC进行项目开发（目前只有MSVC可以直接使用module）。

1. 打开CLion并选择`File -> Open`，然后选择`f-cpp-project`目录。

2. 在CLion中配置MSVC工具链：
   - 选择`File -> Settings`。
   - 导航到`Build, Execution, Deployment -> Toolchains`。
   - 点击`+`按钮添加一个新的工具链，并选择`Visual Studio`。
   - 输入本地安装的`Visual Studio`安装目录。
   
3. 配置CMake：
   - 选择`File -> Settings`。
   - 导航到`Build, Execution, Deployment -> CMake`。
   - 修改`生成器`为`让CMake决定`。
   - 点击`重置缓存并重新加载CMake项目`
   
4. 加载项目并构建：
   - 选择`Build -> Build Project`来构建项目。


