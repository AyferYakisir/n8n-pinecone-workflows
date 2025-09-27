# n8n Pinecone + Google Sheets Workflow

Bu repo, Google Sheets’ten verileri alıp Pinecone’a vektörleştirme ve Pinecone tabanlı bir Chat Agent oluşturma işlemlerini içeren **n8n workflow**’larını barındırmaktadır.  

## İçindekiler
- `workflow_sheets_to_pinecone.json`: Google Sheets → Embedding → Pinecone aktarımı
- `workflow_chat_agent.json`: Pinecone veritabanı ile Chat Agent oluşturma

## Kaynak
Bu workflow, [Youtube: Build Your Own AI Agent with n8n, OpenAI and Pinecone](https://youtu.be/L4hkCzCT30c?si=jKkSteqanQIJpREH) videosundan esinlenilerek oluşturulmuştur.   

## Kullanım
1. n8n üzerinde workflow’ları import edin.  
2. Google Sheets, Pinecone ve LLM API anahtarlarını kendi bilgilerinize göre düzenleyin.  
3. Workflow’u çalıştırarak sistemi test edin.
