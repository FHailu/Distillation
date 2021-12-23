# Distillation
This app takes a feed containing a binary mixture, and outputs the distillate / bottoms flow rates of the distillation column and the feed state. 

You will need to input the antoine coefficients for both components. This will help determine the bubble and dew temperatures within the column, and then help 
define the feed state.

The desired composition of the more volatile compoenent in the distillate & bottoms, this will help determine the flow rates in both leaving streams.

Other Notes / Assumptions:
You will need to load 5 images, that will be included in the submission, so that the code works. The images offer a visual representation of what’s occurring 
at the feed tray, as in whether it travels towards the top or bottom of the column. A quick description is also offered in the image. This app follows 
McCabe-Thiele’s assumptions and assumes that the entering feed acts ideally (so that we can use the Antoine equation/coefficients). Here is an example output 
a user would see for a binary mixture of ethanol and water:

           <img width="519" alt="ExampleDistillationOutput" src="https://user-images.githubusercontent.com/92535248/147286375-61dc0faf-b08c-4be5-a272-7b36117ec58f.PNG">

