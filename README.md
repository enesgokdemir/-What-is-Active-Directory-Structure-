# What is Active Directory Structure? (Aktif Dizin Yapısı Nedir?)

### Aktif Dizin Yapısı Nedir? – Kurum Ağında Kullanıcı Hesabı Türleri ve Aktif Dizin Güvenliği

Aktif Dizin (Active Directory), kurumların ağında yer alan kullanıcı hesaplarının tanımlandığı ve gerekli yetkilerin ilgili kullanıcılarla eşleştirildiği bir yapıdır. Aktif Dizin yapısı esasen bir LDAP veritabanıdır.

Aktif Dizin yapısı ile tanımlanan kullanıcı hesapları, bilgisayar bağımsız bir şekilde ağda oturum açabilir. Örneğin John Doe kullanıcısı, için Bilgi İşlem Departmanı’nda ki bir bilgisayardan kullanıcı hesabı oluşturulmuş olsun. John Doe, Pazarlama Departmanı’nda ki iş bilgisayarından veya ağdaki farklı bir konumdaki bilgisayardan kendi hesabına giriş yaparak ağ kaynaklarına yetkileri çerçevesinde erişim sağlayabilir.

### Kullanıcı Hesabı Nedir?

Kullanıcı hesabı, kullanıcıların sistemelerde oturum açarak hakları çerçevesinde kaynaklara erişmesini sağlayan yapıdır. Kullanıcı hesapları tanımlandığı noktaya göre **Yerel Kullanıcı** hesabı ve **Domain Kullanıcısı** olarak 2’ye ayrılmaktadır.

- **Yerel Kullanıcı**: Yerel kullanıcılar sadece tanımlandıkları bilgisayar çerçevesinde kaynaklara erişim sağlayabilirler. Örneğin ağda yer alan farklı bir bilgisayardaki kaynaklara erişemezler. Yerel kullanıcı hesapları, Windows işletim sisteminde SAM (Security Account Manager) veritabanında tutulurlar.
- **Domain Kullanıcısı**: Domain kullanıcısı, Aktif Dizin yapısı üzerinde oluşturulan kullanıcıyı ifade etmektedir. Domain kullanıcıları bilgisayar bağımsız bir şekilde kurum ağında oturum açabilir ve ağdaki kaynaklara yetkileri dahilinde erişim sağlayabilir. Domain kullanıcıları kurum ağındaki bir bilgisayardan, kullanıcı adı ve parolasını Domain Controller’a (Etki Alanı Denetleyicisi) belirterek ağa dahil olabilirler.

### Aktif Dizin Yapısı Neden Kullanılır?

Microsoft tarafından geliştirilen Aktif Dizin yapısı, en karmaşık kurum ağlarını bile yönetimi kolay hale getirmek için tasarlanmıştır. 10.000 kullanıcılı bir ağda bile Aktif Dizin hizmetinin oluşturduğu hiyerarşik yapı sayesinde kullanıcılarınızı kolaylıkla yönetebilir ve gerekli kaynaklara erişimlerini sağlayabilirsiniz.

### Aktif Dizin Güvenliği

Yerel Ağ Sızma Testi hizmetleri kapsamında Aktif Dizin yapısının güvenliği de incelenmektedir. Aktif Dizin yapısının güvenliğini artırmak amacıyla düzenli periyotlarla yerel ağ pentest hizmeti alınması önerilmektedir. Bununla birlikte kurumların uygulayabileceği bazı sıkılaştırma teknikleri bulunmaktadır:

- Varsayılan güvenlik ayarlarında kalmamalı, en iyi sıkılaştırma teknikleri uygulanmalı ve Aktif Dizin yapısı sürekli güncel tutulmalıdır.
- Aktif Dizin’de yer alan kullanıcılar için en düşük yetkiler verilmelidir. Kullanıcılar sadece girmesi gerektiği kaynaklara erişebilmelidir.
- Aktif Dizin yapısı sürekli takip edilmeli, mümkünse bir güvenlik ürünüyle entegre edilmelidir. Bu yapıdaki değişiklikler ilgili kişilere e-posta yoluyla alarm olarak üretilebilir.
- Aktif Dizin kullanıcıları için güçlü parola kullanımı sağlanmalıdır.
