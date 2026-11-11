# STM32F411_Project

## Hardware
#### - 블록도
![이미지추가](img/blockdiagram.PNG)<br> "블록도"

#### - 회로도
![이미지추가](img/circuitSchematic.PNG)<br> "회로도"

#### - 거버파일
![이미지추가](img/gerber_pcb.PNG)<br> "거버파일"

#### - 3D배치
![이미지추가](img/3dboard.PNG)<br> "3D배치"

### STM32F411MX
#### - RCC 설정
![이미지추가](img/RCCsettings.png)<br>

#### - Clock 설정 
![이미지추가](img/Clocksettings.png)<br>

#### - STM32F411IDE 설정
![이미지추가](img/STM32F411IDEsettings.png)<br>

# STM32F411_Project

## Hardware
---
![이미지추가](img/슬라이드1.PNG)<br> "블록도"
```c
#include <stdio.h>

  /* USER CODE BEGIN WHILE */
  while (1)
  {
	  HAL_GPIO_WritePin(GPIOA, GPIO_PIN_5, 1);
	  HAL_Delay(500);
	  HAL_GPIO_WritePin(GPIOA, GPIO_PIN_5, 0);
	  HAL_Delay(500);
    /* USER CODE END WHILE */

    /* USER CODE BEGIN 3 */
  }
  /* USER CODE END 3 */
 ``` 
## Software
---

## GPIO

