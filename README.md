# Lab3_Compis
Laboratorio 3: Uso de ANTLR para Parsear Terraform y Administrar Droplets de DigitalOcean

---

```
https://uvggt-my.sharepoint.com/:w:/r/personal/gar22434_uvg_edu_gt/Documents/Lab%203%20Compiladores.docx?d=wc886704d42214a5da1e2f737483db069&csf=1&web=1&e=UGBc5S
```

---

## Comandos usados:

Creando alias:
```bash
alias antlr4='java -Xmx500M -cp "/usr/local/lib/antlr-4.13.1-complete.jar:$CLASSPATH" org.antlr.v4.Tool'
```

Compilación de la gramática
```bash
antlr4 -Dlanguage=Python3 'nombre del archivo .g4'
```

Para correr el driver:
```bash
python3 'drive correspondiente'.py 
```
