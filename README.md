## *JAVASCRIPT 💻*

ㅤWith greater proximity to the backend sector during the course, *"JavaScript"* became my main programming language to be used, not eliminating the possibility of projects with other languages. Through it, we can generate different objectives in systems, such as *API* management, creation of *ENDPOINTS*, etc. Using the *"NODE.JS"* interpreter, we can solve all the processes listed in the text and integrate BACKEND into a complete project.
##
*EXAMPLE...*
```js
app.put("/quarto/:id", (req, res) => {
  const id = parseInt(req.params.id);
  const Tipo = req.body.Tipo;
  const Descricao = req.body.Descricao;
  const Preco = req.body.Preco;
  execSQLQuery(
    `UPDATE quarto SET Tipo='${Tipo}', Descricao='${Descricao}', Preco=${Preco} WHERE id_quarto=${id}`,
    res
  );
  res.json(req.body);
});

```
