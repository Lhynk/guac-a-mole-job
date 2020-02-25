# guac-a-mole-job
<h1>Repository for Hack-A-Job 2020-03</h1>
<h3>Ejercicio #001 <small>(El sumas y restas le dicen)</small></h3>
<ol>
  <li>Clone the repository "master" branch</li>
  <li>Create a local branch from master with your team name / your name</li>
  <li>Create a .NET Core 3.1 console application named Palabra</li>
  <li>The code will receive 3 inputs:
    <ul>
      <li>A (signed) integer, example:  -20</li>
      <li>An operator word from the following list:  sumale, restale, multiplicale, divide</li>
      <li>A sentence separated by underscores with the other operator with numbers in spanish, examples: treinta_y_tres, veinte_y_cinco, noventa_y_nueve  the input range will go from uno (1)  to noventa_y_nueve (99)</li>
    </ul>
  </li>
  <li>The code will translate the operator and the sentence into an operator / integer combination and print the result example: Palabra.exe  55 multiplicale cincuenta_y_cinco   must print 3025</li>
  <li>If the result is a fractional number you must print the decimals (no need to specify decimal precision)</li>
  <li>you must validate  Divide by zero</li>
  <li>You must print error messages for invalid inputs accordingly</li>
</ol>
