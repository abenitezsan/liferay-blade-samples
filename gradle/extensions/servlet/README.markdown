# OSGi Whiteboard Servlet

This sample demonstrate how to implement an OSGi Whiteboard Serlvet in Liferay 7

## Usage
1. Set up Liferay Workspace.
2. Go to ```${liferay_workspace_root}/modules``` and clone this repository
3. Go to the root folder of this repository that you just cloned
4. Start up your Liferay bundle
5. Run ```gradle deploy``` and place the generated jar into ```${liferay_home}/deploy``` or if you have ```blade``` installed, run ```blade deploy```
6. Sign in to Liferay as Administrator
7. Navigate to Control Panel -> Configuration -> Server Administration -> Log Levels -> Add Category
8. Configure ```com.liferay.blade.samples.servlet.BladeServlet``` and the log level to ```INFO```
9. Access to ```http://localhost:8080/o/blade/servlet``` You'll see "Hello World" and info log on your console.