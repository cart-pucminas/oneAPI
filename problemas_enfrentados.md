# 🛠 Problemas Enfrentados e Soluções

Este documento é um registro colaborativo de todos os obstáculos técnicos, bugs e desafios de configuração encontrados durante o desenvolvimento com **Intel oneAPI**. 

O objetivo é evitar a redundância de esforços: se você encontrou um problema e o resolveu, documente-o aqui. Se estiver travado em algo, este deve ser seu primeiro lugar de busca.

> [!TIP]
> * **Encontrou a solução?** Registre-a aqui seguindo o template.
> * **Ainda está com o problema?** Abra uma **Issue** no GitHub para que possamos ajudar.
> * **Mudanças no projeto?** Consulte sempre o `README.md` para as últimas novidades.

* ## 📝 Sugestão de Modelo (livre)

### [Título Curto do Problema]
**Descrição:** Explique o erro ou comportamento inesperado. Se possível, cole o log de erro.\
**Resolução:** Passo a passo do que foi feito para corrigir (comandos, troca de flags, ajustes de código ou ambiente).\
**Data:** Quando ocorreu o problema.\
**Autor:** Nome (opcional)

---

## ✅ Exemplos e Registros

### Erro: Compilador `icpx` não encontrado (Command not found)\
**Descrição:** Ao tentar compilar um código SYCL, o terminal retorna que o comando `icpx` não existe, mesmo após a instalação do oneAPI Base Toolkit.  \
**Resolução:** O ambiente do oneAPI não foi inicializado na sessão atual do terminal. Execute o script de variáveis de ambiente:
```bash
source /opt/intel/oneapi/setvars.sh
```  
**Data:**\
**Autor:**  

---
