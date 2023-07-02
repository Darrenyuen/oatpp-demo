## Run OATPP
以下是在macOS上编译oatpp的步骤：
1. 安装CMake：您可以从https://cmake.org/download/下载最新版本的CMake，并按照指示进行安装。
2. 安装依赖项：运行以下命令安装oatpp所需的依赖项：
```
brew install openssl
brew install boost
```
3. 克隆oatpp存储库：您可以从https://github.com/oatpp/oatpp下载oatpp存储库，或者使用以下命令克隆oatpp存储库：
```
git clone https://github.com/oatpp/oatpp.git
```
4. 进入oatpp目录：使用cd命令进入oatpp目录。
5. 创建build目录并进入：在oatpp目录中，使用以下命令创建build目录并进入：
```
mkdir build && cd build
```
6. 运行CMake：使用以下命令运行CMake：
```
cmake ..
```
7. 运行make：使用以下命令运行make进行编译：
```
make
```
8. 安装oatpp：使用以下命令将oatpp安装到系统中：
```
sudo make install
```
完成以上步骤后，您应该已经成功在macOS上编译并安装了oatpp。

## 玫瑰花语

一个留言板
### 玫瑰花语

一个留言板