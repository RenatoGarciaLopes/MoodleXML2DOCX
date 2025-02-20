# 📄 Moodle XML to DOCX Converter

**Descrição:** Ferramenta para converter arquivos de questões **XML** do **Moodle** em documentos **DOCX** formatados, preservando as questões e alternativas de múltipla escolha.

## 🚀 Funcionalidades  
✅ Converte arquivos `.xml` exportados do Moodle para `.docx`  
✅ Mantém a formatação original das perguntas  
✅ Identifica a alternativa correta e a destaca em **negrito**  
✅ Facilita a edição e revisão de questões offline  

## 📦 Instalação  
1. Clone o repositório:  
   ```bash
   git clone https://github.com/RenatoGarciaLopes/MoodleXML2DOCX.git
   cd MoodleXML2DOCX
   ```  
2. Instale as dependências:  
   ```bash
   pip install python-docx
   ```  

## 📂 Como Usar  
1. Coloque os arquivos **.xml** exportados do Moodle na pasta `BQS/`  
2. Execute o script:  
   ```bash
   python program.py
   ```  
3. Os documentos gerados estarão na pasta `BQS_CONV/`  

## 📝 Formato do XML de Entrada  
O arquivo XML deve estar no formato exportado pelo Moodle. Exemplo:

```xml
<question type="multichoice">
    <name>
        <text>O que é a Revolução Industrial?</text>
    </name>
    <answer fraction="100">
        <text>Um período de avanços tecnológicos e produção em massa.</text>
    </answer>
    <answer fraction="0">
        <text>Um movimento artístico do século XIX.</text>
    </answer>
</question>
```

## 📜 Licença  
Este projeto está licenciado sob a **MIT License** – veja o arquivo [LICENSE](LICENSE) para mais detalhes.
