# Eradication-Remediation
Eradication &amp; Remediation


																		TryHackMe - Eradication & Remediation 
																		=====================================


Task 3  Eradication Techniques
==============================

Automated Eradication
---------------------

Bəzi zərərli proqramlar Anti-Viruslar (AV) və EDR kimi alətlər vasitəsilə avtomatik karantinə alına, təmizlənə və silinə bilər. Bununla belə, unutmayın ki, bu, tanınmış zərərli alətlərdən istifadə edən daha az mürəkkəb təhdidlər üçün ən təsirli olur. Daha mürəkkəb pis adamlar tərəfindən istifadə edilən unikal və ya hədəflənmiş təhlükələr adətən bu avtomatlaşdırılmış aşkarlama və qarşısının alınması sistemlərindən yan keçmək üçün məqsədli şəkildə qurulur və buna görə də yalnız bu üsula etibar etmək tövsiyə edilmir.

Buna baxmayaraq, avtomatlaşdırılmış məhvetmə analitiklərin diqqətini daha mürəkkəb təhlükələrə yönəldə bildiyi bir üstünlükdür.

Complete System Rebuild
-----------------------

Müəyyən son nöqtədən təcavüzkar izlərini aradan qaldırmağın ən sadə yolu onu tamamilə yenidən qurmaqdır. Sistemi hər şeydən təmizləmək sistemin təmiz şiferə malik olmasını təmin edir, lakin mənfi tərəfi bu yanaşmanın mütləq olmasıdır. Bütün 'normal' məzmunlar bütün pis olanlarla birlikdə silinəcək və buna görə də bütün proqramları yenidən quraşdırmaq, bütün konfiqurasiyaları bərpa etmək və bütün silinmiş məlumatları bərpa etmək lazımdır ki, kompromisdən əvvəl olduğu kimi yaxşı işləyir. daha yaxşı.


Nəzərə alın ki, bu yanaşma sistem üçün fasilələr tələb edir. Hansı məhvetmə texnikasının kompromis ssenarisinə daha uyğun olduğuna qərar verərkən, qərara həm də sözügedən resursların icazə verilən dayanma müddəti təsir edir. Bəzi təşkilatların “miras” resursları var ki, burada bir neçə dəqiqəlik fasilə təşkilata milyonlarla dollara başa gələ bilər və buna görə də tam yenidənqurmadan söhbət gedə bilməz.


Targeted System Cleanup
-----------------------

Uğursuzluğun nəticələrinin o qədər böyük olduğu hallar var ki, təhlükəsizlik komandası təcavüzkarın onların artıq aşkar edildiyini və təmizlənməyi gözlədiyini bilməsinə icazə verə bilməz. Daha əvvəl müzakirə edildiyi kimi, təhlükəsizlik qrupunun kartlarını vaxtından əvvəl ortaya qoyması qeyri-adi deyil, yalnız təcavüzkarlar ətraf mühitə olduğundan daha çox zərər verən kəskin tədbirlər görməlidirlər.

Müəyyən bir sistem üçün fasilələrin sadəcə olaraq görünmədiyi hallar var, çünki bu, şirkət üçün çoxlu pul itkisinə səbəb olacaqdır.

Bu cür hallar təbiətcə daha həssasdır və buna görə də hücumçu izlərini təmizləməyin məqsədyönlü yolu kəşfiyyata əsaslanmaqla sürətlə və dəqiqliklə planlaşdırılmalı və icra edilməlidir.

Nəzərə alın ki, bu mərhələdə müvəffəqiyyət əhatə dairəsinin nə qədər yaxşı edildiyindən çox asılıdır. Düzgün olmayan əhatə dairəsinin tələlərinə qayıdaq, əgər təşkilat əhatə dairəsini tələsdirmək qərarına gəlsə və dərhal Eradikasiyaya getsə, bu, nəticədə uğursuzluğa səbəb olacaqdır.


What technique is most effective on less sophisticated threats that employ well-known malicious tooling?
Answer: What technique is most effective on less sophisticated threats that employ well-known malicious tooling?

What technique is the most straightforward way to eradicate attacker traces?
Answer: Complete System Rebuild

What downside does the complete system rebuild technique have? This approach entails what for the system?
Answer: Downtime


Success of a targeted system cleanup is heavily reliant on how well the what has been done?
Answer: Scoping



Task 4  Remediation
===================

Hadisəyə Cavab prosesinin bu mərhələsi təcavüzkar alətlərin və izlərin silinməsi ilə bitmir, əksinə, bu, sadəcə başlanğıcdır. Silinmə üsullarının təsirlərinin davamlı olması üçün onunla birlikdə effektiv Remediasiya və Bərpa strategiyası həyata keçirilməlidir. Bundan əlavə, ideal olaraq üçü birlikdə planlaşdırmalı və nəticədə saat mexanizmi kimi icra edilməlidir.


Remediation
-----------


IR prosesi zamanı təşkilat onların təhlükəsizlik vəziyyəti haqqında çox şey öyrənəcəkdi. Təcavüzkarın ətraf mühitdə inkişaf etməsinə imkan verən zəifliklər və/və ya yanlış konfiqurasiyalar aydın şəkildə müəyyən edilsin deyə, düzgün identifikasiya aparılmalıdır. Digər tərəfdən, təşkilatın harada yaxşı olduğu ilə bağlı bir çox anlayışlar olacaq, məsələn, təhlükə aktorunun aşkarlanması metodu, şəbəkə daxilində görünmə səviyyəsi və təşkilatın son nöqtələri və hətta zərərli davranış aşkar edildikdə cavabın verilmə üsulu.

Bu öyrənmələr ideal olaraq təşkilatın təhlükəsizlik vəziyyətini yaxşılaşdırmaq üçün ətraf mühitdə dəyişikliklər üçün planlar doğuracaq. Bu planlar təşkilatın yaxşı bacardığı şeylər ilə təşkilatın əldən verdiyi və güzəştə getdiyi şeylər arasında körpü yaratmalıdır.

Ümumiyyətlə, tipik bərpa addımları aşağıdakılarla başlayır, lakin bunlarla məhdudlaşmır:




Network Segmentation
--------------------

Xüsusi kompüterlər və alt şəbəkələr arasında yalnız mütləq zəruri rabitənin baş verəcəyi şəkildə hazırlanmış şəbəkə seqmentasiyasını həyata keçirmək, təhlükə aktyorunun oynaya biləcəyi hücum səthini xeyli azaldır.

Effektiv remediasiya planları həmçinin təhlükəsizlik qrupunun şəbəkəni görmə qabiliyyətini artıracaq üsulları həyata keçirəcək. Tətbiq edildikdə, zərərliliyi göstərən qəribə şəbəkə davranışı asanlıqla fərq edilə bilər ki, bu da asan aşkarlama və qarşısının alınması mexanizmlərinə şərait yaradır.



Identity and Access Management Review
Restrict Access to Compromised Accounts
Restrict Access to Highly Privileged Accounts
Patch Management


What should take place in conjunction with Eradication techniques in order for its effects to last? An effective what?
Answer: Remediation and Recovery strategy

What remediation step ensures only absolutely necessary communication takes place between computers and subnets?
Answer: Network Segmentation

What do you call the principle that posits that a user account should have access to only the absolutely necessary pieces of data, applications, or resources?
Answer: Principle of least privilege






Task 5  Recovery
================

Recovery
--------

Sistemləri yenidən onlayn vəziyyətə gətirəcək dəyişikliklərin baş verdiyi yer budur. Bu mərhələdə məqsəd normal biznes əməliyyatlarını davam etdirə bilməkdir və buna görə də yaxşı bir bərpa planı təşkilata bu imkanı verəcəkdir.


Təmizləmə mərhələsində edilən dəyişikliklər təşkilatın təhlükəsizlik mövqeyini gücləndirməyə yönəldilmişdir. Bərpa mərhələsində biz bu səylərin bəhrəsini alırıq, eyni zamanda 1) hamısının düzgün yerinə yetirildiyinə və 2) heç bir daş qalmadığına əmin oluruq.

Continuous Testing and Monitoring
---------------------------------

Zəifliklər, digərləri ilə yanaşı, hücum səthinin sahəsinin azaldılması və yamaqlar vasitəsilə aradan qaldırıldıqdan sonra, təşkilat tətbiq etdikləri remediasiya taktikalarının oxşar xarakterli hücumlara qarşı uyğun olub-olmadığını yoxlamaq üçün testlərdən istifadə etməlidir. Bu, nüfuz testləri və hücum simulyasiyaları vasitəsilə həyata keçirilir.

Bu, mahiyyət etibarı ilə yerinə yetirilən müdafiə əlavələrini ardıcıl olaraq sınaqdan keçirəcək və təkmilləşdirəcək bir geribildirim döngəsi yaradacaqdır. Biz razı qaldıqdan sonra, yalnız bundan sonra bu sistemlərin təhlükəsiz şəkildə yenidən istehsalata qaytarılmasına etibar edə bilərik.

Bununla belə, iş burada dayanmır - bu sınaqların davamlı tətbiqi sayəsində, yalnız yenidən tətbiq olunan sistemlərdə deyil, həm də ümumiyyətlə ətraf mühitin qalan hissəsində, aldığımız dərslərin tam dəyərini əldə edirikmi? hadisədən dərs alır.

Backups
-------

Biz həmçinin bərpa mərhələsində təsirlənmiş sistemlərin funksiyasını normal vəziyyətə qaytarırıq. Beləliklə, təkcə məlumatların deyil, həm də unikal sistemlərin malik olduğu ezoterik quraşdırmaların ehtiyat nüsxələrinin saxlanmasının vacibliyi vurğulanmalıdır. Sonuncu, xüsusilə təhlükəyə məruz qalmış sistem tam sistemin yenidən qurulmasına məruz qaldıqda doğrudur.

Beləliklə, ətraflı sənədlərin olmasının əla olduğunu unutmayın. Bununla belə, bu sənədlərdən avtomatlaşdırılmış quraşdırma skriptləri qurmaq və lazım olanda onu hazırlamaq daha yaxşıdır!

Alternativ: Əgər mühitiniz bulud əsaslıdırsa və ya onun ən azı bir hissəsidirsə, sistemlərin yenilənmiş əsas şəkillərini saxlamaq həmişə ən yaxşısıdır.




Action Plan for Recovery
------------------------

Bütün bu dəyişikliklərin həyata keçirilməsi bir gecədə baş vermir. Bu dəyişikliklərin bəziləri daha sadədir və tez həyata keçirilə bilər, digərləri isə yerinə yetirilmək üçün bir neçə komanda və ardıcıl təsdiq axınını cəlb etməli ola bilər. Bu, həqiqətən də çətin bir işdir, lakin bu, bir yarış deyil və əvvəllər müzakirə edildiyi kimi, davamlı bir prosesdir.

Fəaliyyət planları adətən təşkilatın imkanlarından və planlaşdırma və həyata keçirmək qabiliyyətindən asılı olaraq yaxın, orta və uzunmüddətli dövr üçün nəzərdə tutulur. Yaxın müddətli dəyişikliklər ən kritik dəyişikliklərdən ibarət olmalı və prioritetləşdirilməli və dərhal başlamalıdır. Dərhal dəyərli olanlardan başlamaq da məqsədəuyğundur.





Task 6  Targeted System Cleanup: Identification and Scoping, and Eradication Feedback Loop Exercise
===================================================================================================

root@ip-10-10-123-191:~# ssh swiftspend_admin@10.10.37.95
The authenticity of host '10.10.37.95 (10.10.37.95)' can't be established.
ECDSA key fingerprint is SHA256:sS68/814GU3JYKlKrvLTdC3QThxmIWSYvxGQpMJltPM.
Are you sure you want to continue connecting (yes/no)? yes
Warning: Permanently added '10.10.37.95' (ECDSA) to the list of known hosts.
swiftspend_admin@10.10.37.95's password: 
Welcome to Ubuntu 22.04.3 LTS (GNU/Linux 5.15.0-82-generic x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage

  System information as of Mon Dec 25 06:10:22 AM UTC 2023

  System load:  0.0               Processes:             106
  Usage of /:   39.2% of 9.75GB   Users logged in:       0
  Memory usage: 14%               IPv4 address for eth0: 10.10.37.95
  Swap usage:   0%


Which account gave the threat actors a foothold on the server?
swiftspend_admin@jenkins:~$ id
uid=1000(swiftspend_admin) gid=1000(thm_admin) groups=1000(thm_admin),4(adm),24(cdrom),27(sudo),30(dip),46(plugdev),110(lxd)
swiftspend_admin@jenkins:~$ whoami
swiftspend_admin
Answer: swiftspend_admin

What is the default password for the admin account of the Jenkins service?
swiftspend_admin@jenkins:~$ cd /var/lib
swiftspend_admin@jenkins:/var/lib$ ls
amazon  cloud              dpkg   jenkins    misc        plymouth  shells.state  tpm                      ucf                  update-notifier  vim
apport  command-not-found  fwupd  landscape  os-prober   polkit-1  snapd         ubuntu-advantage         udisks2              upower           vmware
apt     dbus               git    logrotate  PackageKit  private   sudo          ubuntu-drivers-common    unattended-upgrades  usb_modeswitch
boltd   dhcp               grub   man-db     pam         python    systemd       ubuntu-release-upgrader  update-manager       usbutils
swiftspend_admin@jenkins:/var/lib$ cd jenkins/
swiftspend_admin@jenkins:/var/lib/jenkins$ ls
backup.sh                       jenkins.install.InstallUtil.lastExecVersion     logs              secret.key                users
config.xml                      jenkins.install.UpgradeWizard.state             nodeMonitors.xml  secret.key.not-so-secret  workspace
hudson.model.UpdateCenter.xml   jenkins.model.JenkinsLocationConfiguration.xml  nodes             secrets
hudson.plugins.git.GitTool.xml  jenkins.telemetry.Correlator.xml                plugins           updates
identity.key.enc                jobs                                            queue.xml.bak     userContent
swiftspend_admin@jenkins:/var/lib/jenkins$ sudo su
[sudo] password for swiftspend_admin: 
root@jenkins:/var/lib/jenkins# cd secrets
root@jenkins:/var/lib/jenkins/secrets# ls
hudson.console.AnnotatedLargeText.consoleAnnotator  hudson.util.Secret               master.key
hudson.console.ConsoleNote.MAC                      initialAdminPassword             org.jenkinsci.main.modules.instance_identity.InstanceIdentity.KEY
hudson.model.Job.serverCookie                       jenkins.model.Jenkins.crumbSalt
root@jenkins:/var/lib/jenkins/secrets# cat initialAdminPassword
f4fe137aeb154299ab1b7349952f6088
Answer: f4fe137aeb154299ab1b7349952f6088


What is the email address of the other account within the Jenkins service?
root@jenkins:/var/lib/jenkins/secrets# cd ..
root@jenkins:/var/lib/jenkins# cd users
root@jenkins:/var/lib/jenkins/users# ls
admin_17026156214276373646  infraadmin_228839177270308121  users.xml
root@jenkins:/var/lib/jenkins/users# cat users.xml 
<?xml version='1.1' encoding='UTF-8'?>
<hudson.model.UserIdMapper>
  <version>1</version>
  <idToDirectoryNameMap class="concurrent-hash-map">
    <entry>
      <string>infra_admin</string>
      <string>infraadmin_228839177270308121</string>
    </entry>
    <entry>
      <string>admin</string>
      <string>admin_17026156214276373646</string>
    </entry>
  </idToDirectoryNameMap>
</hudson.model.UserIdMapper>root@jenkins:/var/lib/jenkins/users# ls
admin_17026156214276373646  infraadmin_228839177270308121  users.xml
root@jenkins:/var/lib/jenkins/users# cd admin_17026156214276373646/
root@jenkins:/var/lib/jenkins/users/admin_17026156214276373646# ls
config.xml
root@jenkins:/var/lib/jenkins/users/admin_17026156214276373646# cat config.xml 
<?xml version='1.1' encoding='UTF-8'?>
<user>
  <version>10</version>
  <id>admin</id>
  <fullName>admin</fullName>
  <properties>
    <jenkins.security.ApiTokenProperty>
      <tokenStore>
        <tokenList/>
      </tokenStore>
    </jenkins.security.ApiTokenProperty>
    <hudson.model.MyViewsProperty>
      <views>
        <hudson.model.AllView>
          <owner class="hudson.model.MyViewsProperty" reference="../../.."/>
          <name>all</name>
          <filterExecutors>false</filterExecutors>
          <filterQueue>false</filterQueue>
          <properties class="hudson.model.View$PropertyList"/>
        </hudson.model.AllView>
      </views>
    </hudson.model.MyViewsProperty>
    <hudson.model.PaneStatusProperties>
      <collapsed/>
    </hudson.model.PaneStatusProperties>
    <jenkins.security.seed.UserSeedProperty>
      <seed>008807ec84730e36</seed>
    </jenkins.security.seed.UserSeedProperty>
    <hudson.search.UserSearchProperty>
      <insensitiveSearch>true</insensitiveSearch>
    </hudson.search.UserSearchProperty>
    <hudson.model.TimeZoneProperty/>
    <jenkins.model.experimentalflags.UserExperimentalFlagsProperty>
      <flags/>
    </jenkins.model.experimentalflags.UserExperimentalFlagsProperty>
    <hudson.security.HudsonPrivateSecurityRealm_-Details>
      <passwordHash>#jbcrypt:$2a$10$MCIWiZysP2jGG3D1mEAIfeDY5DRySnMUqacfIUFn39C2dK5qK9cFi</passwordHash>
    </hudson.security.HudsonPrivateSecurityRealm_-Details>
    <jenkins.security.LastGrantedAuthoritiesProperty>
      <roles>
        <string>authenticated</string>
      </roles>
      <timestamp>1693352029175</timestamp>
    </jenkins.security.LastGrantedAuthoritiesProperty>
  </properties>
Answer: infra_admin@swiftspend.finance


What is the command being invoked by the project found in the Jenkins dashboard?
root@jenkins:/var/lib/jenkins/users# cd ..
root@jenkins:/var/lib/jenkins# cd jobs
root@jenkins:/var/lib/jenkins/jobs# ls
BackUp
root@jenkins:/var/lib/jenkins/jobs# cd BackUp/
root@jenkins:/var/lib/jenkins/jobs/BackUp# ls
builds  config.xml  nextBuildNumber
root@jenkins:/var/lib/jenkins/jobs/BackUp# cat config.xml 
<?xml version='1.1' encoding='UTF-8'?>
<project>
  <actions/>
  <description>Scheduled backup for jenkins</description>
  <keepDependencies>false</keepDependencies>
  <properties/>
  <scm class="hudson.scm.NullSCM"/>
  <canRoam>true</canRoam>
  <disabled>false</disabled>
  <blockBuildWhenDownstreamBuilding>false</blockBuildWhenDownstreamBuilding>
  <blockBuildWhenUpstreamBuilding>false</blockBuildWhenUpstreamBuilding>
  <triggers>
    <hudson.triggers.TimerTrigger>
      <spec>H 0 1 * *</spec>
    </hudson.triggers.TimerTrigger>
  </triggers>
  <concurrentBuild>false</concurrentBuild>
  <builders>
    <hudson.tasks.Shell>
      <command>/bin/bash /var/lib/jenkins/backup.sh</command>
      <configuredLocalRules/>
    </hudson.tasks.Shell>
  </builders>
  <publishers/>
  <buildWrappers/>
Answer: /bin/bash /var/lib/jenkins/backup.sh


How many times has the project been run before?
Answer: 0


You will find a suspicious IP address. Which country is it hosted in? (Use AbuseIPDB; answer as written)
root@jenkins:/var/lib/jenkins/jobs/BackUp# cat /etc/hosts
127.0.0.1 localhost
127.0.1.1 jenkins
194.26.135.132 backup.swiftspend.com

# The following lines are desirable for IPv6 capable hosts
::1     ip6-localhost ip6-loopback
fe00::0 ip6-localnet
ff00::0 ip6-mcastprefix
ff02::1 ip6-allnodes
ff02::2 ip6-allrouters
https://www.abuseipdb.com/check/194.26.135.132
Answer: Russian Federation


Based on the MITRE ATT&CK Matrix, which Tactic is being applied by the threat actor here?
Answer: Exfiltration


Based on the Lockheed Martin version of the cyber kill chain, in what phase is the threat actor already in on this server?
Answer: Actions on Objectives

