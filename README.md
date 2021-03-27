- 👋 Hi, I’m @kkanz99
- I’m use os Android
- Source from Google

<!---
kkanz99/kkanz99 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Answer:

1.definisi,DevOps adalah serangkaian praktik yang mengotomatiskan proses antara pengembangan aplikasi dan tim pengembang agar mereka dapat melakukan proses build, test dan release perangkat lunak lebih cepat dan lebih handal.

Manfaat penting DevOps di suatu perusahaan:
sebagai pengembangan perangkat lunak dari Agile yang meninjau untuk lebih melayani banyak pelanggan, manajemen produk hingga produk pengembang.

serta,gambarkan flow DevOps development:
GitHub Version Control | Master > Pull download & create local feature branch | Feature XYZ > Develop create PR > Pull request

flow DevOps production:
On AWS, Internet download Server | server upbalancer Internet, on Server, Availability zone A or Availability zone B to GCP sentiasa, On GCP Snapshot backups

2 . perbedaan,

AWS:
Virtual Servers EC2
Dockers ECS
Scalability AWS Scaling
Load Balancing Elastic Load Balancing
API EC2 API
GUI Console
Storage Object S3
Block Storage EBS
Networking Networking
Compute VM
Security/Identity I AM
Orchestration CloudFormation
Archiving Glacier
Image Templates Amazon Machine Images
DNS Management Router 53
Relational Database RDP

OpenStack:
Virtual Servers Nova Instance
Dockers Magnum
Scalability Heat with Scaling
Load Balancing LBaas
API OpenStack API
GUI Horizon
Storage Object Swift
Block Storage Cinder
Networking Neutron
Compute Instance
Security/Identity KeyStone
Orchestration Heat
Archiving Swift
Image Templates Glance
DNS Management Designate
Relational Database Trove

3.Git adalah perangkat lunak pengendali versi atau proyek manajemen kode perangkat lunak yang diciptakan oleh Linus Torvalds, yang pada awalnya ditujukan untuk pengembangan kernel Linux. Desain Git terinspirasi oleh BitKeeper dan Monotone.

Cara Kerja:

+ Fork & Clone Repository:

1.Fork:
Fork will create a copy of the repository in your Github account so that you can make changes to the projects.

2.Clone:
Clone will make a local copy

+ Modification Repository:

1.Modification:
Modification will change of the repository.

+ Push Repository

1.Push:
Push will upload local repository content to a remote repository.

+ Pull request repository:

1.Pull request:
Pull request will proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch.

4.Continuous Integration/Continuous Development diperlukan menerapkan perubahan perangkat lunak

gambaran diagram kerja Continuous Integration/Continuous Development:
Code > Commit > Sector CIpipeline, Build > Unit test > Intergration Test > Sector CIPipeline, review > Staging > Production.

5.Perbedaan,Private Cloud dengan Public Cloud

Private Cloud:
Private Cloud digunakan untuk kebutuhan bisnis dengan menyertakan sumber daya khusus bersifat private.

Public Cloud:
Public Cloud digunakan untuk operasi yang tidak sensitif, sehingga tidak menimbulkan sesuatu yang berisiko.

6.Tool Monitoring Server yang digunakan:

Tool bernama Ganglia, Keuntungan:
+ Menghasilkan data analisis yang terukur dan mudah didistribusi.
+ Platform monitoring yang solid
+ Mendukung banyak operating system dan Processor
+ Cluster besar di seluruh di dunia menggunakan platform ini, terutama di lingkungan universitas.

7.Infrastruktur Server yang baik dan benar untuk microservices:

       Phone   Rest API | Trip Management - Rest API | Billing | Stripe Adapter
         |     / 
User - Gateway API - Rest API | Passenger Management -----------------
                     /                                               |
      Computer - Passenger Web UI - Rest API | Driver Management - Rest API | Payments
         \                                           |     \ 
        Driver Web UI --------------------------------   ¦ Rest API | Notification | Sendgrip Adapter | Twilio Adapter

8. #Iam use Android
