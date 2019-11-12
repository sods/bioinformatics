---
layout: page
title: FAQs
---

<img src="{{ site.url }}{{ site.baseurl }}/assets/faq.png" width="50%"/>

### Frequently Asked Questions

This is a list of frequent questions asked accross time by students of BMS353. You might find them useful and they could be your first point of call prior posting on the Feedback forum. This forum can be found in the **Feedback** tab of this website. a good advice id to *try to evaluate your problem frst and find a solution*, since this is part of training youself to code.   

1. **How do I change my kernel?** Go on the notebook horizontal bar menu and choose Kernel->Change Kernel -> R(SageMath)


2. **After restarting my code not work any more.** After a kernel restart you must execute (shift+enter) all your previous code cells. This is because a restart of the kernel wipes your workspace of all the objects. 


3. **I am trying to press execute the code cell but I get a message saying 'Trying to evaluate using lr-sage' or 'Waiting for another computer to finish first'**. This is the case of a conflit in the kernel, either you have a mistake in the code to have crashed the kernel or accidentally a conflict was created. Restart your kernel and execute the cells up to the point you got stuck. Debug that point or use alternative code.


4. **Are markdown cells necessary if we use in code commenting?** The aim of your notebook is to create a document where you embed the code within the interpretation of the data. It is not a mere coding excise. The notebook is like a report, a paper if you wish. In the markdown cells you need to add this part and the comments related to the code are within the code cells. 
In this sense the markdown cells are absolutely crucial and the notebook will also be evaluated on clarity and interpretation of the data. 


5. **What do I do if the execution gets stuck?** The most best option is to restart the kernel. Be aware that after restart you need to execute all the cells. See question 2.

6. **What are the PM and MM in the Affymetrix chip and what are they for?** The scope of the microarrays is to quantify the gene expression levels and therefore to quantify copies of mRNA related to each gene they probe. Affymetrix does this using synthetic oligonucleotides, that cover a region around the poly A tail of each gene. They use 25bp long window to cover that region. They create a set of 11 matching oligos (Perfect Match- PM) and 11 mismatch oligos where the middle base 13th is changed with its complementary (Mismatch- MM). In total 22 synthetic oligos for each gene. The cDNA will bind to them and the more it binds the more mRNA of that gene there was in the sample. The flourescence attached to these oligos is then captured by a scanner and the level of flourescence intensity quantify the gene expression. The PM capture the mRNA copies and the MM the noise. 

6. **I am having a delay when typing in the cells. They are not responding as quickly as I expected.** Sometimes teh browser you are using might interfere with the GUI of teh system. This problem you are mentinoning seems to be happening with Explore Edge Browser. Try to use a different browser like Firefox or Chrome. If you are using already these browsers, reset them and open a new session maybe and incognito window to avoid cookies and other fetures that might delay the browser. 
