# Online Kernel Learning

    The OGD software was obtained from the following website as a subset (i.e., C++ source code only):

    https://github.com/LIBOL/KOL

    The software was modified to add the Isolation Kernel compoments.

# Additional Command line parameters

   ## Batch mode:
    * -opt KERNEL-IK_OGD
    * -ik_model <aNNE, iNNE, iForest, DotProduct> : DotProduct is for pre-generated data file.
    * -ik_psi <value>
    * -ik_sets <value>


   ## Online mode:
    * -ik_mode_online : to select online mode
    * -ik_ol_init_bk_size : the initial training size
    * -ik_ol_acc_bk : output the accuracy after 'x' number of blocks


# Additional Note

    The original OGD software is rather fragile. For example, if the number of data points within a data file is a multiple of 256, then the program could crash. I haven't attempted to supply any fixes to the original software.

# References

Ting, Kai Ming, Jonathan R. Wells, and Takashi Washio. "Isolation kernel: the X factor in efficient and effective large scale online kernel learning." Data Mining and Knowledge Discovery 35.6 (2021): 2282-2312.[[pdf]](https://github.com/IsolationKernel/Codes/blob/main/PDF/Isolation%20Kernel-The%20X%20Factor%20in%20Efficient%20and%20Effective%20Large%20Scale%20Online%20Kernel%20Learning.pdf)
