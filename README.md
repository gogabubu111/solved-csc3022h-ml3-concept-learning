Download Link: https://assignmentchef.com/product/solved-csc3022h-ml3-concept-learning
<br>
Implement (in C++) the FIND-S algorithm (chapter 2 [Mitchell, 1997]). Use the training examples in table 1 to verify that it successfully produces the trace described in section 2.4 [Mitchell, 1997] for the <em>Enjoysport</em> example. <strong>Q1:</strong> Now use this program to determine the number of additional training examples required to exactly learn the target concept:

<em>&lt;</em> <em>Sunny,</em> <em>W</em> <em>arm,</em> ?<em>,</em> ?<em>,</em> ?<em>,</em> ? <em>&gt;</em>

In a ZIP file, place the source code, executable, and a text file containing your list of random training examples and the answer to Q1. Upload ZIP file to <em>Vula</em> before 10.00 AM, 19 August.

Table 1: Positive and negative training examples for target concept EnjoySport

<table width="509">

 <tbody>

  <tr>

   <td width="67">Example</td>

   <td width="52">Sky</td>

   <td width="68">AirTemp</td>

   <td width="71">Humidity</td>

   <td width="54">Wind</td>

   <td width="51">Water</td>

   <td width="64">Forecast</td>

   <td width="82">EnjoySport</td>

  </tr>

  <tr>

   <td width="67">1</td>

   <td width="52">Sunny</td>

   <td width="68">Warm</td>

   <td width="71">Normal</td>

   <td width="54">Strong</td>

   <td width="51">Warm</td>

   <td width="64">Same</td>

   <td width="82">Yes</td>

  </tr>

  <tr>

   <td width="67">2</td>

   <td width="52">Sunny</td>

   <td width="68">Warm</td>

   <td width="71">High</td>

   <td width="54">Strong</td>

   <td width="51">Warm</td>

   <td width="64">Same</td>

   <td width="82">Yes</td>

  </tr>

  <tr>

   <td width="67">3</td>

   <td width="52">Rainy</td>

   <td width="68">Cold</td>

   <td width="71">High</td>

   <td width="54">Strong</td>

   <td width="51">Warm</td>

   <td width="64">Change</td>

   <td width="82">No</td>

  </tr>

  <tr>

   <td width="67">4</td>

   <td width="52">Sunny</td>

   <td width="68">Warm</td>

   <td width="71">High</td>

   <td width="54">Strong</td>

   <td width="51">Cool</td>

   <td width="64">Change</td>

   <td width="82">Yes</td>

  </tr>

 </tbody>

</table>

1

<strong>References</strong>

[Mitchell, 1997] Mitchell, T. (1997). <em>Machine Learning</em>. McGraw Hill, New York, USA.