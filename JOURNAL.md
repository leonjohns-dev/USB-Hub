Day 2 - PCB finished

I have officially finished the project. I decorated it with some cool-looking stuff, but I don't think it will become a reality. Firstly, it is pretty expensive; secondly, there are a lot of part shortages when I checked with the JLC PCB website, so that also puts this to an end. It was pretty cool designing my own PCB, and I hope to make more!
<img width="980" height="571" alt="image" src="https://github.com/user-attachments/assets/edbbd771-1b40-47a4-8d81-8ed9421e530a" />



Day 2 - Cleared DRC test

I have finally cleared all DRC fails, and my PCB is ready. It was difficult, as I had 2 major problems; first, I had to fix a differential pair routing that was caused by a different tolerance value that was different from the guide. After searching settings, I was able to change the value and do proper differential pair routing. The next problem was the copper pour for GND. I myself don't know how I solved it; I reapplied the pour after putting my GND holes, which solved it.
<img width="1534" height="690" alt="image" src="https://github.com/user-attachments/assets/62443692-57aa-450f-a91f-4197a6eea727" />


Day 2 - DRC Failed

I had completed everything yesterday; today, as preparation for the final steps, I ran the DRC test. I got 60 errors; I have decided to redo the PCB build now. I am not sure what the source of the error is, but I think it is one of the poor layers, but nonetheless, I will be redoing it

<img width="1536" height="724" alt="image" src="https://github.com/user-attachments/assets/5995c5e2-fca8-480b-930c-9c144659a206" />



Day 1 - Continued (Design the PCB)

I have continued working on the project, and now I have finally sorted out all the components the best way for the easiest routing. I chose the shape of my PCB to be similar to the guide since I really loved the techy design on it; it makes it look like a Flipper Zero.

This process was very tedious for me since I had to switch the data positive and data negative of my downstream USBs a lot of times to accommodate proper routing. Knowing that the PCB will be two layers, I don't think this will be a big issue. I look forward to a peaceful routing session.

Time spent: 1 hour 30 minutes.

<img width="1529" height="727" alt="image" src="https://github.com/user-attachments/assets/31ed3b6d-90d8-4795-b3f3-8c084be7e905" />


Day 1

Today, I have finished my schematic for my USB hub PCB. I have learned a lot about PCB designing in just this hour, such as the net label feature, which I had never used while attempting to make a PCB design.

One mistake I made in this session was the improper placement of the GND and VDD before knowing about the preferred guideline of placing VDD up and GND down. I had been placing them to look more aesthetically pleasing, but after learning about my mistake, I repaired to fit the guidelines.

Overall, it was fun learning to make a schematic for a PCB!

Total Time spend: 1 hour 11 minutes

<img width="1532" height="727" alt="image" src="https://github.com/user-attachments/assets/7711b5a4-82c5-48fe-9ffd-e251e50a9e79" />
