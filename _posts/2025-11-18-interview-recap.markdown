---
layout: post
title:  "Interview Recap and Tips"
date:   2025-12-10 20:40:12 +0530
categories: Notes
---

TODO : need to parse the content properly

This is for basically noting down what went wrong, right, and what I can do to improve. Need to check where I am lacking and also to prepare for what needs to be done during the interview process.

Lets start with what all interviews I have given and what are the learnings 


1. 247 AI 
2. Foundation AI 
3. Some intersting company : very interesting quesitons 
4. ZEISS 
5. Meesho



<details>
<summary> Meesho Interview </summary>


- Things to be covered here : 
    - SQL queries 
        - rank functions, window functions 
    - Leet code more practice
    - End to End training from scratch
    - pyspark (not necessary)
    - Over fitting and under fitting how and why
    - Class imbalance how to handle
    - Central Limit Theorem
    -  
 

        53. Maximum Subarray


        Given an integer array nums, find the subarray with the largest sum, and return its sum.

        Example 1:
        Input: nums = [-2,1,-3,4,-1,2,1,-5,4]
        Output: 6
        Explanation: The subarray [4,-1,2,1] has the largest sum 6.


        Example 2:
        Input: nums = [1]
        Output: 1
        Explanation: The subarray [1] has the largest sum 1.


        Example 3:
        Input: nums = [5,4,-1,7,8]
        Output: 23
        Explanation: The subarray [5,4,-1,7,8] has the largest sum 23.


        #############################


        result = -inf
        temp = {}
        for i in ele : 
            result  = max(result,i)


        ============================

        Implement pow(x, n), which calculates x raised to the power n (i.e., xn). 
        Example 1:
        Input: x = 2.00000, n = 10
        Output: 1024.00000

        Example 2:
        Input: x = 2.10000, n = 3
        Output: 9.26100
        n_ = abs(n)


        for i in range(n_) : 

        ##########################

        # customer table 
        Customer ID int 
        Name varchar
        City varchar 

        # order_table 
        Order ID
        Customer ID
        Order Date
        Order Total / Amount


        Find the total number of orders placed by each customer, excluding orders placed in June.

        -> Customer ID, Order ID, Order date 

            -> Customer Name, Number of Order 
                (DD/MM/YYYY)
        ->  
            select cm.customer_name , count(order-id)
            from customer_master cm
            join order_table ot
            on cm.customer_id = order.customer_id
            where  '01-06-2025' < ot.order_date < '31-06-2025'
            group by customer_id

        -> 
            select customer_id, sum(order_amount) ,  as rank  as total_amount 
            from order_table group by customer_id order by total_amount desc

            rank function ? 
            
        -> window functions ? 

        left vs left anti join 



        select * , customer_city from customer_master
        # default 

        # pyspark ? 



        [8*32] -> 8,32

        [8,32,32]

        1 feature -> x - mean / variance 

        mean = sum  / count --> running mean and variance (scale and shift)
</details>