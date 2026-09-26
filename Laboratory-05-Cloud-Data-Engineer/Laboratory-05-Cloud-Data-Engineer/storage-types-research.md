# Cloud Storage Types Comparison

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| **Block Storage** | Hinahati ang datos sa maliliit na bloke, bawat isa ay may sariling address. Mabilis basahin at baguhin, parang hiwalay na hard drive. | Mga database, operating system, apps na kailangan ng mabilis na pagbasa at pagsulat | AWS EBS, Azure Managed Disks, GCP Persistent Disk |
| **File Storage** | Nakaayos sa mga folder at file na parang karaniwang computer. May malinaw na istruktura na madaling makita. | Shared drives, pampamilyang folder, file server sa opisina | AWS EFS, Azure Files, GCP Filestore |
| **Object Storage** | Bawat file ay isang "object" na may kasamang paglalarawan (metadata) at natatanging ID. Hindi nakasali sa folder, nakaimbak sa "bucket". Kayang lumawak nang napakalaki. | Mga larawan, video, backup, malalaking datos, nilalaman ng website | AWS S3, MinIO, Azure Blob Storage, GCP Cloud Storage |

---

## Bakit Object Storage ang pinakamainam?

Ang object storage ang pinakaangkop para sa iyong app dahil dinisenyo ito para mag-imbak ng napakaraming larawan nang mura, ligtas, at madaling ma-access sa internet. Hindi tulad ng ibang uri, kayang lumawak nang walang hangganan — kaya kahit dumami pa ang gagamit, hindi magkakaroon ng problema sa espasyo.
