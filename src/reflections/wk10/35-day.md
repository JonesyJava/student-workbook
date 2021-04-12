# Day 35 - Week 10
## C-Sharp Intro

## What is an Enum, and what are some use cases for them?
Enum is "enumerable" and used to count from 1 to 1. It is used within a Range of data within an index to be returned. 
## How can you modify an Enum?
You can used "splitOn" within the return. This will allow for a split within returned enum and will join at this margin within the List. 

## How have you used Enums in your afternoon lab projects this far?(if you have not yet, give an example of how you could)
[HttpGet]
        public ActionResult<IEnumerable<Blog>> GetAll()
        {
            try
            {
                return Ok(_service.GetAll());
            }
            catch (System.Exception err)
            {
                return BadRequest(err.Message);
            }
        }