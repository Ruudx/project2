<!DOCTYPE html>
<html>
<HTML lang="en-us">

<head>
<style>
table, th, td
  {
    border: 10px solid black;
    background-color: white;

  }

thead
  {
    color:black;
    font-family: Papyrus;
  }
caption
  {
    color: black;
    font-family:Papyrus;
    font-size: 300%;
  }
tbody
  {
    color: black;
    font-family:Papyrus;
  }
tfoot
  {
    color: black;
    font-family:Papyrus;
  }

<title>"My Music"</title>
<meta charset="utf-8">

</style>
</head>

/* ===========================================================================
=========================================================================== */

<body>

<DIV id=”mytable”>

  /* <!-- The <thead> tag is used to group header content in an
  HTML table. The <thead> element is used in conjunction with the
  <tbody> and <tfoot> elements to specify each part of a table --> */
  <table>

    <caption><b>My Favorite Bands<b></caption>
    <caption>
    </caption>

    <thead>
      <tr>
        <th>Artists</th>
        <th>Musicians</th>        <!--Column headers-->
        <th>Album</th>
      </tr>
    </thead>

  /* <!-- The <tbody> tag is used to group the body content in an HTML table.
  The <tbody> tag must be used in the following context: As a child of a
  <table> element, after any <caption>, <colgroup>, and <thead> elements. --> */
  <tbody>
    <tr>
      <td><a href="https://www.russiancirclesband.com/">Russian<br>Circles</a></td>
      <td>Mike Sullivan<br>Brian Cook<br>Dave Turncrantz</td>                                            <!--Row One-->
      <td>
        <img src="russiancircles.jpg"
        alt="Russian Circles" width="300" height="300">
      </td>
    </tr>

    <tr>
      <td><a href="https://www.toolband.com/">Tool</a></td>
      <td>Maynard James Keenan<br>Adam Jones<br>Danny Carey<br>Justin Chancellor</td>                        <!--Row Two-->
      <td>
        <img src="tool.jpg"
        alt="Tool" width="300" height="300">
      </td>
    </tr>

    <tr>
      <td><a href="https://www.deftones.com/">Deftones</a></td>
      <td>Chino Moreno<br>Abe Cunningham<br>Frank Delgado<br>Sergio Vega<br>Stephen Carpenter</td>           <!--Row Three-->
      <td>
        <img src="deftones.jpg"
        alt="Deftones" width="300" height="300">
      </td>
    </tr>

    <tr>
      <td><a href="https://www.Ween.com/">Ween</a></td>
      <td>Gene Ween<br>Dean Ween<br>Dave Dreiwitz<br>Claude Coleman Jr<br>Glenn McClelland</td>             <!--Row Four-->
      <td>
        <img src="ween.jpg"
        alt="Ween" width="300" height="300">
      </td>
    </tr>

    <tr>
      <td><a href="http://www.primusville.com//">Primus</a></td>
      <td>Les Claypool<br>Larry LaLonde<br>Tim Alexander</td>                                              <!--Row Five-->
      <td>
        <img src="primus.jpg"
        alt="Primus" width="300" height="300">
      </td>
    </tr>

  </tbody>

  /* ===========================================================================
  =========================================================================== */

  /* <!-- The <tfoot> tag is used to group footer content in an HTML table.
  The <tfoot> tag must be used in the following context: As a child of a
  <table> element, after any <caption>, <colgroup>, <thead>, and <tbody> elements. --> */
  <tfoot>
    <tr>
      <td colspan="3">"These Bands are Awesome!"</td>             <!--colspan makes it so the attached message spans over all three columns-->
    </tr>
  </tfoot>
</table>


</Div>
</body>
</html>
