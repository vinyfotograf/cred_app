<h1>Instructions for running the application<h1>

<h3>Here is a sample of project created with flask api</h3>

<p>O aplicativo recebe uma entrada em json e realiza as validações necessárias para aprovação de uma transação</p>

<ul>
    <li>When the value of installmets exceeds 30% of income: compromised-income</li>
    <li>When the score is lower than 200: low-score</li>
    <li>When the istallments value is lower than 6: minimum-installments</li>
    <li>When happens two transactions in the same 2 minutes: doubled-transactions</li>
</ul>

<p>To store the transaction, Flask-Caching was used<p>
<a href="https://flask-caching.readthedocs.io/en/latest/" >More<a>






