/**
  @page ride RIDE Project Template for STM32F0xx devices

  @verbatim
  ******************* (C) COPYRIGHT 2014 STMicroelectronics ********************
  * @file    readme.txt
  * @author  MCD Application Team
  * @version V1.3.1
  * @date    17-January-2014
  * @brief   This sub-directory contains all the user-modifiable files needed
  *          to create a new project linked with the STM32F0xx Standard Peripheral 
  *          Library and working with RIDE7 software toolchain
  ******************************************************************************
  *
  * Licensed under MCD-ST Liberty SW License Agreement V2, (the "License");
  * You may not use this file except in compliance with the License.
  * You may obtain a copy of the License at:
  *
  *        http://www.st.com/software_license_agreement_liberty_v2
  *
  * Unless required by applicable law or agreed to in writing, software 
  * distributed under the License is distributed on an "AS IS" BASIS, 
  * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  * See the License for the specific language governing permissions and
  * limitations under the License.
  *
  ******************************************************************************
   @endverbatim
 
 @par Directory contents
 
 - project .rprj/.rapp: A pre-configured project file with the provided library 
                        structure that produces an executable image with RIDE7.

 @par How to use it ?
 
 - Open the Project.rprj project.
 - In the configuration toolbar(Project->properties) select the project config:
     - STM32F051: to configure the project for STM32F051 devices.
                  You can use STMicroelectronics STM320518-EVAL or STM32F0-Discovery
                  board to run this project.
     - STM32F031: to configure the project for STM32F031 devices.
                  You need to use custom HW board to run this project.
     - STM32F030: to configure the project for STM32F030 devices.
                  You can use STMicroelectronics STM32F0308-Discovery board to run this project.
     - STM32F072: to configure the project for STM32F072 devices.
                  You can use STMicroelectronics STM32072B-EVAL.             
 - Rebuild all files: Project->build project
 - Load project image: Debug->start(ctrl+D)
 - Run program: Debug->Run(ctrl+F9) 
 
 @note The needed define symbols for this config are already declared in the
      preprocessor section: USE_STDPERIPH_DRIVER, STM32F0XX, USE_STM320XXX_EVAL

 * <h3><center>&copy; COPYRIGHT STMicroelectronics</center></h3>
 */


