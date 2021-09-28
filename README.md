<h1> Alura Challenge BI </h1>
<h2> Week 01: Logistics Challenge - Alura Log </h2>

> The manager of the logistics departmente at Alura log is facing some changes due to the increased demand caused by the corona virus pandemic. He wants to maintain service quality, so he needs to constantly monitor his department's metrics to make the best decisions. To help with this challenge, I created a dashboard for logistics with some important metrics for the area.


<h3> Database </h3>
<hr>
The database provided by Alura log has the following .csv files:

<h4> Tabela Pedidos </h4>
<p>Contains the record of all orders placed by customers.</p>

<div align="center">
  
<table>
  <thead>
    <tr>
      <th> Variable </th>
      <th> Description </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td> Data do Pedido </td>
      <td> purchase order date </td>
    </tr>
    <tr>
      <td> Data de entrega </td>
      <td> delivery date </td>
    </tr>
     <tr>
      <td> Data previsão de entrega</td>
      <td> expected delivery date </td>
    </tr>
     <tr>
      <td> ID pedido </td>
      <td> rrder ID </td>
    </tr>
     <tr>
      <td> Latitude </td>
      <td> latitude </td>
    </tr>
     <tr>
      <td> Longitude </td>
      <td> longitude </td>
    </tr>
     <tr>
      <td> UF de entrega </td>
      <td> UF delivery </td>
    </tr>
     <tr>
      <td> ID produto  </td>
      <td> Product ID  </td>
    </tr>
     <tr>
      <td> Quantidade </td>
      <td> Quantity of products </td>
    </tr>
    <tr>
      <td> ID veículo </td>
      <td> Vehicle ID </td>
    </tr>
</tbody>
</table>
</div>  
<h4> Tabela Produtos </h4>
Contains the record of products and their values.

<div align="center">
  <table>
    <thead>
      <tr>
        <th> Variable </th>
        <th> Description </th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td> ID Produto </td>
        <td> Product ID </td>
      </tr>
      <tr>
        <td> Categoria do produto </td>
        <td> Product Category </td>
      </tr>
      <tr>
        <td> Valor </td>
        <td> Price </td>
      </tr>
    </tbody>
  </table>
</div>  

<h4> Tabela Veículos </h4>
Contains the record of vehicle used to transport products.

<div align="center">
  <table>
    <thead>
      <tr>
        <th> Variable </th>
        <th> Description </th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td> ID Veículo </td>
        <td> Vehicle ID </td>
      </tr>
      <tr>
        <td> Data de atualização </td>
        <td> Update date </td>
      </tr>
      <tr>
        <td> Quantidade </td>
        <td> Quantity of vehicles </td>
      </tr>
    </tbody>
  </table>
</div>  

<h4> Tabela de Estoque </h4>
Contais product inventory by month.

<div align="center">
  <table>
    <thead>
      <tr>
        <th> Variable </th>
        <th> Description </th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td> ID Produto </td>
        <td> Product ID </td>
      </tr>
      <tr>
        <td> Data de atualização </td>
        <td> Update date </td>
      </tr>
      <tr>
        <td> Quantidade </td>
        <td> Quantity of vehicles </td>
      </tr>
    </tbody>
  </table>
</div>  

<h3> Metrics </h3><hr>


  <dl>
  <dt> Entregas no prazo </dt>
  <dd>- On-time deliveries </dd>
  <dt> Entregas atrasadas </dt>
  <dd>- Delayed deliveries </dd>
  <dt> Veículos disponíveis para entrega </dt>
  <dd>- Vehicles available for deliver </dd>
  <dt> S2D </dt>
  <dd>- Ship to door</dd>
  <dt> Índice de ocorrências por estado </dt>
  <dd>- Rate of occurrences by state</dd>
  <dt> Média do estoque </dt>
  <dd>- Stock average</dd>
  <dt> Estoque disponível por Categoria </dt>
  <dd>- Stock available by Category</dd>

</dl>

<h3> Dashboard </h3> <hr>
<p align="center">
  <img src="figuras\screenshot-semana-1.png" width="850" title="dashboard-aba-geral">
</p>

<h3> Link </h3> <hr>
https://app.powerbi.com/view?r=eyJrIjoiMTkyMmVlZjUtNjM2OS00ODVjLWEyYTEtNDg5MDUxZTNmNDFhIiwidCI6IjExZTcxNzgzLWMyZWEtNGZlZS04MzE4LTcxMjJmMThkNzUzNCJ9&pageName=ReportSection
