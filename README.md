# 第二次作业
## 任务一
类图：http://www.plantuml.com/plantuml/png/Z5J1RXCn4BtdAqOzkMhw0qGWg1HA9THKIHkG40VlPbWCZhsoPw4bDD-ErsEllAkeuZGlRsRztemzUUj9Ekhs6l2nrjBxsIm6kEggIkF6Ea9tc04079MXBrz1yeyDEMKQQBKqy1hEpfZzPTKE_6_PYb0CQWvz-74UanSngQtSYNHIoVkW91AHpcwGxiBnWNtEhguH_sG_Xs2TLFryP1BeEp8QPIzIDXnsdmjO9_SGdBJIUOnQHLldHKluY7L7cDEUi1sPH-992GxWOnYtevN1XrPy327Ys1QQRW_NjdCxRcfrkupn_jEAuuVrafdtguSrWvijCvkRpnoNs-NjS4NWvj3CeHfF8KhqGuZWwcajpKyHgmD8FlFFoJMGPI0c7TzPhqXP8pA0De5KEF1DKPnomqCP4knG6XlkqHMEmiTRgJlaPn0OTDzaZH3cA2kDX_ysjNZ9rUAKu69uUBrQaZhcZ_ftaw0lJBGTYUGDD4TU0vMQoicW8vX_QTovFAYHVUUSV2ht8Nj9rYQwuz6avDJSPAnvuqzkB6hSeo6VnrLixkBawl88o_yIkBpy-mOIVWN_zgnlwTF-nK_NpNlUju4Bb3inLNGlVJQdy_sUZfSDdS-wLpxhc_HqL_-pQJkVxkb_lwUJ2vni85gW7aCt5HHrO0Nmq0AgU3bZ_fCTQv_FQdcoj_VvtdKlPxSzdT311LE0OTxy2Kzsh88eVThM2jJsh6F2quapkBYu75BpKe359m00  

时序图：http://www.plantuml.com/plantuml/png/SoWkIImgAStDuL80WiJaalmY1VVKrAhK8eN4OX0BMJo_j2Z542JkduSXRWGI3odFHnSt1ejd566QP0AISGEoq2LCmHAPPHWwp40ImPaLwEBcOF7KijGyi4ngNabcIQM2JsPUAaYYi3IrD9KBBECF5D6rWuWeM2cys3_xQUlIvslMc3_PiUh9tjxdUzU1b86yWLMP2OeoYAzqxJ2K6Q4e0tiHcsbcACh07iQcp1X56SZxMDrcYg8C4XfOt6Q8K0PMvmxqWQuTaBHwsh7XsTobx_Vql6peVDQzybdVfAUx-c5ge2PPGKKTKlDIW6a60000

设计理念：  
利用linable接口来实现一个行元素可以执行的操作，因而可以实现多个元素共用一个接口，实现代码的复用，并且利用private与类中的接口来实现对类中元素的保护。  

好处：  
可以让代码复用性更强，而且对程序有一定保护能力。在进行排序交换时，利用一个数组进行排序与交换，最后将交换记录传出，让类自己根据记录交换，对象自己执行自己的操作，有助于代码封装。

## 任务二
类图：http://www.plantuml.com/plantuml/png/p5HDanCX4BtdLtJjYTIwlo2bvNhnuc4rwiNom4pQY65WX1wDhjdVBj1GwHbJrXvtBhpf3tZlGVNBI3hGD5Z0OszrZAjLMU3M4eQj3tI_WlGz64UVFeFcdoq5u_OmMktWELnTSVI7Dpk8F_MeKZ6OPv2NR-kIl2v9w_LErPraFAPpL0tKlVT8Tsdx53qrIg-chhEOEM5uEgpUJgO_F0bIiknxOrKEA9VCXw3RrRhyDrv82ssl4NytMVUfYan_Uk0Wq5TaDCjUrspYzBuLgBMq8WaQTOXOA0jtri8PF68_4RPq91nd7Y2nuOeNY6MPksADmm-ZUfEMWgKi7xeKEbyN13ZZlS2TAD7k87MKG2nmnGVV-MZ8U9V5Dwncl4My0HWh4BUI-ZzgEw5evjVIch8gtLa4o-jSENa6QWrPyqftYQRk2LXzxQtg_-71rzbwJeyWlbcqNFPXMJKNkip-Lp9ca5hgZRAcfQ3ypYgCmiPnegLx_F9DDR4cCpSbuqjpv-NfDFAt8UXVSZOqBfNQujpvowZ99RcoM-A1uOlk4UgWkJmeqEA0Zc9rKmwCpUM9iJbptVReK6uyw0E-qsxd1zQLpHYCOxS6VMJG-ybH8Id7CzpS_7a15V-TbSAplgLF-nS_NJVlUTy6BdZDWayHk5GbR1QeWC5KqRtqsPpEztiwNZPqFkjU-QnlqjDT_S-cxNowf__zdaukQEw7Q8A6Db3NyztBdtNkVzQrzyN6XSytxkO29Icm6dWi0XMzd37_oOwrpsUrFDdR-tplkfUpsvvEwE22Ai0myjdy2Kzsh88eVThM2jJsh6F2quapk21AC8o7g8UeWTl1nUK0B9I1DJG0

可视化视频：https://asciinema.org/a/R49Ky6o7ApF7LFS9AxB1GwDUE

## 任务三
类图：http://www.plantuml.com/plantuml/png/p5NDSjCm4BxdANPwigVj4sHWQ2zSOAOGuC9ma9qbYCYIaMIQKj9dPosjaxLZEZas5wtsH_g-RzVAcn2LZrrZ07UrKI4i5cc16nFHhvoFZmkWtvEsyUitK7cpYbxR3RH6MNW55nVP-zlfDOHxrHQK3FeA-kLdcOANAMYSMXTyalG7kgTW1v-zmNX7nvDtFq2wxQhAO8y9_Sj1zQ7JzVP5W99flmPKwOBKv7m9sZNdzRjs9YoulKNyCz1wfAoew_rJTaByWTaQHIyvIfW-3Gb5AQKWGgto0HDaeKufbC4Trbt48HmYjYCDC6R1Yxn0ICjO5QCjVcwBTxGaUnnj5AqxYhzF1kybTUShAZks53mSxOsmAv6Yx5PoJOwGp4M-_iu57RMpgMbi5oDkmdz8RjaGdQFwByfqA8hpH1sgYRcg397FwvX_TDaeIkWvBrH5C5KT8RFdMcP_WYEtVAZPdm5yEIcPrs6Q9OcUHf-bZBr19SUEKd1Ag9z5DeEGiUtYLBtyTMWMSGWIjeBzy-AEqkcsw6wyLmyYWA2ylttugEm6d_yOywJAWNJtOWnhP_BcCF4yShcku8ehuEJo7CAUqyzADgwUruSZy-FtNudWI7te5vEVt3x-UZWuXPY492pelwiQWH_i-GSN3JPeOoYN9m_lSlxbNHwnhcgqA0zkr1QflMlN9699a4RRh5cZTaD7EXiJIFat1zVNVry3s__wB8CS1O4WYkxh59o3rHnj5WEX1mOO5uQeaH1334Q9B4nG85w6ggPNNC4EhRLWmVxztvLE__fjMnJc61smtClm2jpGIn2tqxANMTHpmizf9yRMKz-2_8B25JuYMj-nZSPMm7j36j7djcrBDaSIJ_hjXYgJLGFJSvmOphnjgIJjwulS_FJTd-nAjNKnze21cIMbSL-V38gkesNanVYVW45czYmm41y29WXiFWsR5YgvwL4mSCW_3ra0yALZfpz4Bm00

可视化视频：https://asciinema.org/a/ScmIgySwfL2yb3CG9O2BINSvt
