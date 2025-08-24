# ☁️ Utilização do Storage Account no Microsoft Azure

## ✨ Introdução

O **Storage Account** é um serviço fundamental do Microsoft Azure que permite armazenar objetos de dados como blobs, arquivos, filas e tabelas. Ele oferece alta disponibilidade, segurança, escalabilidade e acesso global via HTTP/HTTPS.

Este projeto demonstra como criar, configurar e utilizar uma conta de armazenamento no Azure, incluindo o uso de **File Share**, tipos de redundância e camadas de acesso.

---

## 🛠️ Recursos Utilizados

- 🔹 **Azure Portal**  
  Interface gráfica para gerenciamento dos recursos de nuvem.

- 🔹 **Storage Account**  
  Recurso que centraliza os serviços de armazenamento como Blob, File Share, Queue e Table.

- 🔹 **Azure File Share**  
  Compartilhamento de arquivos em nuvem com suporte a mapeamento de rede SMB/NFS.

---

## 🚀 Como Criar uma Storage Account

1. Acesse o [Portal do Azure](https://portal.azure.com)
2. Clique em **"Create Resource"** e selecione **"Storage Account"**
3. Preencha os campos:
   - Resource Group
   - Nome da Storage Account (sem caracteres especiais)
   - Região
   - Tipo de desempenho (Standard ou Premium)
   - Tipo de redundância (LRS, GRS, ZRS, etc.)
   - Access Tier (Hot, Cool, Archive)

4. Clique em **"Review + Create"** e finalize o deploy

---

## 📁 Criando um Azure File Share

1. Dentro da Storage Account criada, vá até **"File Share"**
2. Clique em **"New File Share"**
3. Defina o nome e a cota de armazenamento
4. Clique em **"Create"**

Agora você pode:
- Criar diretórios
- Fazer upload de arquivos
- Mapear o File Share como uma unidade de rede no seu computador

---

## 🔗 Mapeando o File Share no Windows

1. Acesse o File Share
2. Clique em **"Connect"**
3. Copie o script gerado (PowerShell ou CMD)
4. Execute no seu computador para montar a unidade

---

## 📊 Tipos de Storage e Redundância

| Tipo de Armazenamento | Serviços Compatíveis | Redundância | Indicado Para |
|------------------------|----------------------|-------------|----------------|
| Uso Geral v2           | Blob, File, Queue, Table | LRS, GRS, ZRS | Cenários comuns |
| Blobs Premium          | Blob de bloco         | LRS, ZRS     | Alta performance |
| File Share Premium     | Arquivos do Azure     | LRS, ZRS     | Aplicações empresariais |
| Blobs de Página Premium| Blobs de página       | LRS, ZRS     | Discos gerenciados |

Fonte: [Documentação oficial do Azure Storage](https://learn.microsoft.com/pt-br/azure/storage/common/storage-account-overview)

---

## 📎 Links Úteis

- 🔗 [Criar Storage Account e File Share – Tutorial prático](https://www.nathanpinotti.com.br/como-criar-uma-storage-account-e-file-share-no-azure/)
- 🔗 [Documentação oficial do Azure Storage](https://learn.microsoft.com/pt-br/azure/storage/common/storage-account-overview)
- 🔗 [Vídeo: Como utilizar Storage Account no Azure](https://www.youtube.com/watch?v=mNI8q24J9YE)

---

## ✅ Conclusão

O Azure Storage Account é uma solução poderosa para armazenar dados de forma segura, escalável e acessível. Com recursos como File Share, redundância geográfica e integração com redes locais, ele se adapta a diversos cenários — de backups simples a aplicações empresariais de alto desempenho.

---

