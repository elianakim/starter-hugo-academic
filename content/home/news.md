+++
widget = "blank"
headless = true
active = true
weight = 20

title = "News"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.spacing]
  padding = ["10px", "0", "10px", "0"]
+++
<style>
td, th {
  border: none!important;
  vertical-align: top;
}

.news {
  font-size: 20px;
}

@media only screen and (max-width: 768px) {
  .news {
    font-size: 16px;
  } 
}
</style>

<!-- <div style="margin-left: 10%; margin-right: 10%;"> -->

<table class="news">
         <tr>
            <th></th>
            <th></th>
         </tr>
         <tr>
            <td><b>Sep. 2022</b> &nbsp; &nbsp; &nbsp; &nbsp;</td>
            <td>:tulip: Paper accepted at NeurIPS 2022</td>
         </tr>
         <tr>
            <td><b>Jul. 2022</b> &nbsp; &nbsp; &nbsp; &nbsp;</td>
            <td>:trophy: Won the Students with Outstanding Questions Award of KAIST</td>
         </tr>
         <tr>
            <td><b>Feb. 2022</b> &nbsp; &nbsp; &nbsp; &nbsp;</td>
            <td>:four_leaf_clover: Joined Networking & Mobile Systems Lab as a Master's Student</td>
         </tr>
         <tr>
            <td><b>Feb. 2022</b> &nbsp; &nbsp; &nbsp; &nbsp;</td>
            <td>:mortar_board: Graduated from KAIST with honors</td>
         </tr>
      </table>

<!-- |                      |               | 
| :------------------- | :------------ | 
| **Jul. 2022** &nbsp; &nbsp; &nbsp; &nbsp; | :trophy: Won the Students with Outstanding Questions Award of KAIST | 
| **Feb. 2022** &nbsp; &nbsp; &nbsp; &nbsp; | :four_leaf_clover: Joined Networking & Mobile Systems Lab as a Master's Student | 
| **Feb. 2022** &nbsp; &nbsp; &nbsp; &nbsp; | :mortar_board: Graduated from KAIST with honors |  -->

<!-- </div> -->