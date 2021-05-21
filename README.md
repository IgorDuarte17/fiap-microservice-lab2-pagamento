# FIAP - Microservices (Hands-On) | LAB 2 Pagamento

---

## Conteiner Pagamento
> docker build -t pagamentoimg .  
> docker run --name pagamento -p 8080:8080 -d pagamentoimg

### Exemplo de chamada no navegador:
http://localhost:8080/pagamento?tipo_pagamento=DINHEIRO&valor_pagamento=500  
http://localhost:8080/pagamento?tipo_pagamento=CHEQUE&valor_pagamento=500  
http://localhost:8080/pagamento?tipo_pagamento=DINHEIRO&valor_pagamento=500  
