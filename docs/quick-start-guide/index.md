# Quick Start Guide

We have outlined some simple steps to guide you through configuring your project. You can run a project in a short amount of time.

#### **1. Create a Project**

Click the "Add" button in the project list to create a project.

![img](https://docs.wagoscada.cn/wiki/api/wiki/editor/QHXVK91b/YB1ge5e1/resources/21V1JZuFFT8MUrSWZcTV2q0tO5NWZoY3J4LQ6-f2gMU.png?token=W.hrMkmMCPTMLO89vkgmDbxybJoir9Boo_iPEh1rd2jElzeBsABtrlZyX9b9rGOchRiKlcdE_cE8m1ybhVyfRbgR3-2w)

#### **2** **. Add a Database**

After the installation of VC Hub, a SQLite database will be automatically created, which you can use for basic testing. You can also click "Database" -> "Database Connection" page and then click the "New" button to create a new database connection. 

#### **3. Add Assets**

After the installation of VC Hub, a default asset will be automatically created, which you can use for basic testing. You can also click "Tags" -> "Assets" page and then click the "New" button to create new assets.

#### **4. Open the Editor**

On the project list page, click the "Design" button for the project.

![img](https://docs.wagoscada.cn/wiki/api/wiki/editor/QHXVK91b/YB1ge5e1/resources/0wX5BPfsPR7kB_bLrshZudLeksK9ICD9dm2ym8fIYmA.png?token=W.hrMkmMCPTMLO89vkgmDbxybJoir9Boo_iPEh1rd2jElzeBsABtrlZyX9b9rGOchRiKlcdE_cE8m1ybhVyfRbgR3-2w)

Open the configuration editor to display the following interface.

![img](https://docs.wagoscada.cn/wiki/api/wiki/editor/QHXVK91b/YB1ge5e1/resources/Rmz-PR1K6MUeRIoIt0yW7aTxT6npikah5MWnfJi8kW0.png?token=W.hrMkmMCPTMLO89vkgmDbxybJoir9Boo_iPEh1rd2jElzeBsABtrlZyX9b9rGOchRiKlcdE_cE8m1ybhVyfRbgR3-2w)

#### **5. Create a New Page**

Click "New Page" to quickly create a new page.

![img](https://docs.wagoscada.cn/wiki/api/wiki/editor/QHXVK91b/YB1ge5e1/resources/bqsgE-ItRQUqdPkOVMogWaUxkgGE681ZBb3POBaxsT4.png?token=W.hrMkmMCPTMLO89vkgmDbxybJoir9Boo_iPEh1rd2jElzeBsABtrlZyX9b9rGOchRiKlcdE_cE8m1ybhVyfRbgR3-2w)

In the **Tools** window on the left side of the designer, add for example "Rect" , "Label" , "Value Display",and "Historical Trend Chart" controls to the page. You can also use the search functionality.

![img](https://docs.wagoscada.cn/wiki/api/wiki/editor/QHXVK91b/YB1ge5e1/resources/VwWrXRmriVGhiLYFZvItpPpoLah7iUSVzN0SOV5fuUw.png?token=W.hrMkmMCPTMLO89vkgmDbxybJoir9Boo_iPEh1rd2jElzeBsABtrlZyX9b9rGOchRiKlcdE_cE8m1ybhVyfRbgR3-2w)

#### **6. Create a Tag**

In the asset dropdown box of the asset window in the configuration editor, select an asset and then click the add button to add a memory tag to that asset. Tag name: liquid.

![img](https://docs.wagoscada.cn/wiki/api/wiki/editor/QHXVK91b/YB1ge5e1/resources/k1kqHwoJbD-jUm-eL_cFyGLekFGeoZz3QEyIX-TW4co.png?token=W.hrMkmMCPTMLO89vkgmDbxybJoir9Boo_iPEh1rd2jElzeBsABtrlZyX9b9rGOchRiKlcdE_cE8m1ybhVyfRbgR3-2w)

Enable the simulated property for this tag, using simulated value as the tag value. Types supported are **Random**, **Increment**, **Decrement**, and **Fixed.**

![img](https://docs.wagoscada.cn/wiki/api/wiki/editor/QHXVK91b/YB1ge5e1/resources/NSvhW9OBFOU-Q14Mf87RkcmaB4VdYzvkYSSE0vLtiPw.png?token=W.hrMkmMCPTMLO89vkgmDbxybJoir9Boo_iPEh1rd2jElzeBsABtrlZyX9b9rGOchRiKlcdE_cE8m1ybhVyfRbgR3-2w)

#### **7. Enable History for Tags**

At the top of the tag editing page, enable history recording to store the value of the tag historically.

![img](https://docs.wagoscada.cn/wiki/api/wiki/editor/QHXVK91b/YB1ge5e1/resources/tlTSpdWC4EduNrGSgJmTOscymrV5r3xVIuN2d8Xf5v8.png?token=W.hrMkmMCPTMLO89vkgmDbxybJoir9Boo_iPEh1rd2jElzeBsABtrlZyX9b9rGOchRiKlcdE_cE8m1ybhVyfRbgR3-2w)

#### **8. Bind Tag**

Bind tags to controls on the page.

1. Set the display content of the text label to: "Liquid level:"

![img](https://docs.wagoscada.cn/wiki/api/wiki/editor/QHXVK91b/YB1ge5e1/resources/x84YdsVVKC9LA7MCQ-F4YOEIlTM3808KCQ-nEX8_st0.png?token=W.hrMkmMCPTMLO89vkgmDbxybJoir9Boo_iPEh1rd2jElzeBsABtrlZyX9b9rGOchRiKlcdE_cE8m1ybhVyfRbgR3-2w)

2.  In the animation of the rectangle, select the fill animation. Click the value binding button and bind the created tag:liquid.

![img](https://docs.wagoscada.cn/wiki/api/wiki/editor/QHXVK91b/YB1ge5e1/resources/yblwiXQTVWsfulli7TBQd4RcBZSDkoZ96ta8yJe-5yA.png?token=W.hrMkmMCPTMLO89vkgmDbxybJoir9Boo_iPEh1rd2jElzeBsABtrlZyX9b9rGOchRiKlcdE_cE8m1ybhVyfRbgR3-2w)

3. In the value display control, click the value binding button and bind the created tag:liquid. Afte binding, the binding icon will turn from gray to green.

![img](https://docs.wagoscada.cn/wiki/api/wiki/editor/QHXVK91b/YB1ge5e1/resources/J9jOyT5mqZwgcMiitzCYJnt9MNBcXS-QY_ishmHvYd0.png?token=W.hrMkmMCPTMLO89vkgmDbxybJoir9Boo_iPEh1rd2jElzeBsABtrlZyX9b9rGOchRiKlcdE_cE8m1ybhVyfRbgR3-2w)

4. In the historical chart control, click the value binding button and bind the created tag:liquid. 

![img](https://docs.wagoscada.cn/wiki/api/wiki/editor/QHXVK91b/YB1ge5e1/resources/Ct-842HDUfaECEskYNrhwr1CSJ23uivPvwbsf5aDtV8.png?token=W.hrMkmMCPTMLO89vkgmDbxybJoir9Boo_iPEh1rd2jElzeBsABtrlZyX9b9rGOchRiKlcdE_cE8m1ybhVyfRbgR3-2w)

Note: For more information on binding, please refer to the Property Binding page. 

#### **9. Preview/Run**

Click the preview button in the page tool bar to view the preview effect. You can also click the run button for the project in the project list to view the running page.

![img](https://docs.wagoscada.cn/wiki/api/wiki/editor/QHXVK91b/YB1ge5e1/resources/PCquW_p7odGSaeBw_OK_AcHLcEfFEwrrrPWOTbPsp4w.gif?token=W.hrMkmMCPTMLO89vkgmDbxybJoir9Boo_iPEh1rd2jElzeBsABtrlZyX9b9rGOchRiKlcdE_cE8m1ybhVyfRbgR3-2w)



