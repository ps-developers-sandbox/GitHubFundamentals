# 🔨 Hands-on: Code reviews

In this hands-on lab, you will learn how to perform code reviews. 
The exercise consists of the following parts:

- [Getting ready for review](#getting-ready-for-review)
- [Enable auto-merge](#enable-auto-merge)
- [Performing the review](#performing-the-review)

## Getting ready for review

- [ ] Go to **your own pull request** and indicate that you are `Ready for review`: 

<img width="400" alt="image" src="https://user-images.githubusercontent.com/5276337/204331306-bc5efd99-6bcd-4f3a-bd12-869a04d35765.png">

This will change the status of the PR from draft to ready. As we require a review, merging is blocked.

## Enable auto-merge

- [ ] Enable auto-merge for the PR. Note the different merge types - we'll learn later what they mean. Just leave the default.

<img width="400" alt="image" src="https://user-images.githubusercontent.com/5276337/204331468-e218cb92-28f3-42a6-bfa8-270ed9d420df.png">

- [ ] The merge commit needs a commit message - just leave the default and `Confirm auto-merge`: 

<img width="400" alt="image" src="https://user-images.githubusercontent.com/5276337/204331553-050939e7-bc5d-476a-aa9f-e2ee46bcef9f.png">


## Performing the review

> **Note**  
> Wait until your partner from #1 is ready. You'll perform the review for their PR.

- [ ] Go to the PR of your partner from #1 (you should have received a request for review after the status of the pul request was changed)
- [ ] Navigate to `Files changed` and add a comment
- [ ] Select `Start a review` this time.  

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204331933-5d6b0d10-f5b2-427c-adbf-47fa33c18b33.png">

- [ ] Add multiple comments to your review and note that they are pending:

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204332123-0e10b74c-8416-4a45-a85a-8e9dab877ba8.png">

- [ ] When you are ready `Finish your review`. Only approve will merge the PR - all other results will still block the merge.
- [ ] Submit the review:

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204332393-921b01ba-1313-440b-93c3-ccc544f5171c.png">

- [ ] Note that the status automatically changes to `Merged` and the `HEAD` branch gets deleted (that is a setting in the repo).
- [ ] Note that you can revert the changes and restore the deleted branch: 

<img width="600" alt="image" src="https://user-images.githubusercontent.com/5276337/204332909-cf6d5f47-6700-44ab-b501-d778205934d3.png">

Wait until GitHub pages is refreshed and see the results...

## Summary

In this lab you've learned how to perform code reviews and use auto-merge.
You can now go back to [Collaborate on code](../README.md#part-2--collaborate-on-code).
