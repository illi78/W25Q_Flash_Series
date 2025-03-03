## Steps to Set Up  

1. Copy the file **`W25Q_Flash_Series.ioc`** to a folder named **`W25Q_Flash_Series`**.  
2. Run the file **`W25Q_Flash_Series.ioc`** using **STM32CubeMX**.  
3. Click the **Generate** button to create the project.  
4. Copy the **`Core`** folder and merge it with the existing folder.  

---

## Alternative Configuration  

If you are using a different configuration, follow these steps:  

1. Create your project as usual.  
2. Copy the files **`W25Qxx.c`** and **`W25Qxx.h`** to the appropriate locations in your project.  
3. Ensure the correct **SPI channel handler** is selected.  
4. For **Chip-Select (CS)**, choose the correct **port and line** according to your project settings.  
5. Modify the **`csLOW`** and **`csHIGH`** functions accordingly.  
