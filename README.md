# ✅ Testes Desenvolvidos para a suíte de Orientador

Os seguintes testes estão implementados na requisição `POST /api/v1/Orientador/add`:

1. ✅ **Status 200 OK**  
   Verifica se a resposta da API foi bem-sucedida.

2. ✅ **Tempo de resposta < 1s**  
   Garante que a API responde em até 1000 milissegundos.

3. ✅ **Tempo de resposta < 100ms (rigoroso)**  
   Verifica desempenho mais exigente, útil para testes de performance.

4. ✅ **Verificação do campo `type = about:blank`**  
   Confirma que o campo `type` segue o padrão esperado de resposta.

5. ✅ **Verificação do título da resposta não ser `"ERROR"`** *(caso negativo)*  
   Garante que não houve erro interno retornado pela API.

6. ✅ **Resposta possui corpo JSON válido**  
   Valida que a resposta tem conteúdo e que está corretamente formatado como JSON.

---

Esses testes foram implementados utilizando o Postman e validados via linha de comando com o Newman.  
O sistema de autenticação e token CSRF também foi integrado para assegurar o correto funcionamento das requisições.



