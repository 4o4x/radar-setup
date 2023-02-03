## Step 1
 - Download git https://git-scm.com/downloads
## Step 2
- Download these link
	- https://dev.ti.com/tirex/explore/node?node=A__AGvTEJkh-csqqwXnVhDbTQ__radar_toolbox__1AslXXD__LATEST
		- ![[Untitled.png]]
	- https://dev.ti.com/gallery/view/mmwave/mmWave_Demo_Visualizer/ver/3.6.0/
		- Safariye kurulmuyor. Sonra eklenecek resimler.
	- https://dr-download.ti.com/software-development/software-programming-tool/MD-QeJBJLj8gq/8.1.1/uniflash_sl.8.1.1.4146.run


	- https://dr-download.ti.com/software-development/software-development-kit-sdk/MD-PIrUeCYr3X/03.06.00.00-LTS/mmwave_sdk_03_06_00_00-LTS-Linux-x86-Install.bin
		- 64 Bit problem  
		
 
	  
	 

## Step 3

- Download miniconda3 https://docs.conda.io/en/main/miniconda.html
- Close your terminal and open it again
- If you are in base environments
	 ```console
	 $conda deactivate	
	```

- Creating new env
  ```console
	$conda create --name radar_env
  ```
- Activate env
  ```console
	$conda activate radar_env
  ```
- Install python modules
  ```console
	$pip install mediapipe
	$pip install cv2
  ```

## Step 4

Install mmwave_ti_tos
  ```console
~$cd Desktop
  ```

  ```
$ git clone https://git.ti.com/git/mmwave_radar/mmwave_ti_ros.git
  ```


