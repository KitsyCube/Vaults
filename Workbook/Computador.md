## Work Remastering

> [!todo] To-do
> - Make paid column to be a function of (claim - paid), before it adds in headers.
> - Include a more robust check on if paid column was manually entered,,, somehow. Maybe check if it is a function or not?
> - Change the master range to be just "master" instead of "master_2", for slightly easier set-up.
> - Set the minimum amount of variance to be variable, instead of hardcoded.
>-  Auto input reason for variance to be "awaiting remit" for certain groups, if there isn't already a reason.
> - When making AGE worksheet macro, have it be an auto updating function instead of a one-time addition. 
> - Fix when using macro to create an empty line at the top if there isn't.
> - Building output, it adds original row that was there, then an empty row in the start( which might not be working anyways?), then in the loop for outputting it doesn't if it's the first header? Can just combine that to the loop.

> [!question] Ideas
> - Give list of functions as you open workbook? ( might only be actually time-saving when integrated to work with outside of excel ... )
> - When making AGE worksheet macro, disable ( simply copy its value then paste may be easiest if possible? ) the auto updating function for any AGE worksheets older than three months from active AGE worksheet. 
> - Auto make AGE worksheet after main macro?
> - Change sorting to be from a fixed, sorted list? Then don't need to do the whole grouping thing. 
> - Make { ComputeValue } function be able to handle any amount of values, not just three, and maybe which operators between.






