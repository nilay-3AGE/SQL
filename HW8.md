# HW8

1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

```
CREATE TABLE employee (
  id INT NOT NULL,
  name VARCHAR(50),
  birthday DATE,
  email VARCHAR(100)
);

```


2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.


```

insert into MOCK_DATA (id, name, birthday, email) values (1, 'Cristen', '1966-04-30', 'crandalston0@hugedomains.com');
insert into MOCK_DATA (id, name, birthday, email) values (2, 'Meridith', '1950-09-05', 'mchallice1@who.int');
insert into MOCK_DATA (id, name, birthday, email) values (3, 'Verna', '1995-12-07', 'vfountain2@amazonaws.com');
insert into MOCK_DATA (id, name, birthday, email) values (4, 'Dianna', '1904-01-12', 'dflanaghan3@japanpost.jp');
insert into MOCK_DATA (id, name, birthday, email) values (5, 'Nadeen', '1956-12-20', 'nhold4@dion.ne.jp');
insert into MOCK_DATA (id, name, birthday, email) values (6, 'Pierson', '1935-01-17', 'pgrealy5@omniture.com');
insert into MOCK_DATA (id, name, birthday, email) values (7, 'Sidonnie', '2000-03-29', 'scosker6@vk.com');
insert into MOCK_DATA (id, name, birthday, email) values (8, 'Cecil', '1919-01-28', 'cdunkerly7@ihg.com');
insert into MOCK_DATA (id, name, birthday, email) values (9, 'Doralyn', '1901-09-13', 'dmannering8@bing.com');
insert into MOCK_DATA (id, name, birthday, email) values (10, 'Wendie', '1971-07-15', 'wdeaguirre9@nydailynews.com');
insert into MOCK_DATA (id, name, birthday, email) values (11, 'Davina', '1933-03-11', 'djossa@google.com.au');
insert into MOCK_DATA (id, name, birthday, email) values (12, 'Ursulina', '1900-05-18', 'uhillborneb@hugedomains.com');
insert into MOCK_DATA (id, name, birthday, email) values (13, 'Caroline', '1958-07-02', 'ctrangmarc@hp.com');
insert into MOCK_DATA (id, name, birthday, email) values (14, 'Blane', '2002-04-17', 'bdwired@bloglines.com');
insert into MOCK_DATA (id, name, birthday, email) values (15, 'Irwinn', '1933-04-27', 'iseallye@google.de');
insert into MOCK_DATA (id, name, birthday, email) values (16, 'Antonie', '1948-11-16', 'amcwilliamsf@washingtonpost.com');
insert into MOCK_DATA (id, name, birthday, email) values (17, 'Wildon', '1914-11-26', 'wjerokg@jugem.jp');
insert into MOCK_DATA (id, name, birthday, email) values (18, 'Henrik', '1987-02-12', 'htidboldh@discovery.com');
insert into MOCK_DATA (id, name, birthday, email) values (19, 'Hedwiga', '2015-01-12', 'htanguyi@webeden.co.uk');
insert into MOCK_DATA (id, name, birthday, email) values (20, 'Ollie', '1941-10-17', 'oknibbj@comcast.net');
insert into MOCK_DATA (id, name, birthday, email) values (21, 'Dorolisa', '1932-07-14', 'dsuttellk@alibaba.com');
insert into MOCK_DATA (id, name, birthday, email) values (22, 'Eldredge', '1903-03-20', 'efusedalel@google.cn');
insert into MOCK_DATA (id, name, birthday, email) values (23, 'Everard', '1946-10-28', 'eackeroydm@google.es');
insert into MOCK_DATA (id, name, birthday, email) values (24, 'Clerc', '1977-07-23', 'cyakushkinn@ft.com');
insert into MOCK_DATA (id, name, birthday, email) values (25, 'Sky', '1933-11-09', 'sbirkwoodo@rakuten.co.jp');
insert into MOCK_DATA (id, name, birthday, email) values (26, 'Leonerd', '1977-07-11', 'lzellickp@zimbio.com');
insert into MOCK_DATA (id, name, birthday, email) values (27, 'Randene', '2014-08-22', 'rigonetq@arstechnica.com');
insert into MOCK_DATA (id, name, birthday, email) values (28, 'Michail', '2005-05-07', 'mocuddier@de.vu');
insert into MOCK_DATA (id, name, birthday, email) values (29, 'Derry', '2000-11-27', 'dsnels@usda.gov');
insert into MOCK_DATA (id, name, birthday, email) values (30, 'Smith', '1922-02-22', 'sharfleett@google.com.hk');
insert into MOCK_DATA (id, name, birthday, email) values (31, 'Darrick', '1919-08-07', 'dsetchfieldu@networksolutions.com');
insert into MOCK_DATA (id, name, birthday, email) values (32, 'Riccardo', '1912-02-21', 'rhebblewaitev@vimeo.com');
insert into MOCK_DATA (id, name, birthday, email) values (33, 'Salim', '2010-07-22', 'skarpinskiw@studiopress.com');
insert into MOCK_DATA (id, name, birthday, email) values (34, 'Isis', '1988-01-10', 'isnoxallx@google.it');
insert into MOCK_DATA (id, name, birthday, email) values (35, 'Abbie', '1992-05-08', 'apowdrelly@list-manage.com');
insert into MOCK_DATA (id, name, birthday, email) values (36, 'Alameda', '1992-10-26', 'aduchesnez@sohu.com');
insert into MOCK_DATA (id, name, birthday, email) values (37, 'Shaughn', '1960-04-10', 'sbumfrey10@prnewswire.com');
insert into MOCK_DATA (id, name, birthday, email) values (38, 'Bonni', '1925-07-19', 'bemburey11@uol.com.br');
insert into MOCK_DATA (id, name, birthday, email) values (39, 'Birgit', '1942-12-24', 'bvereker12@drupal.org');
insert into MOCK_DATA (id, name, birthday, email) values (40, 'Muffin', '1946-11-14', 'mfernant13@xrea.com');
insert into MOCK_DATA (id, name, birthday, email) values (41, 'Kile', '1923-01-11', 'kzuanazzi14@yellowbook.com');
insert into MOCK_DATA (id, name, birthday, email) values (42, 'Wilton', '2001-08-21', 'wproger15@washington.edu');
insert into MOCK_DATA (id, name, birthday, email) values (43, 'Brittney', '1981-06-01', 'bivanishchev16@yahoo.co.jp');
insert into MOCK_DATA (id, name, birthday, email) values (44, 'Terese', '1992-05-21', 'tvinecombe17@constantcontact.com');
insert into MOCK_DATA (id, name, birthday, email) values (45, 'Martelle', '1915-06-06', 'menoksson18@scribd.com');
insert into MOCK_DATA (id, name, birthday, email) values (46, 'Mikey', '1991-01-30', 'mcoram19@xinhuanet.com');
insert into MOCK_DATA (id, name, birthday, email) values (47, 'Ramsey', '1913-05-07', 'rprestwich1a@pagesperso-orange.fr');
insert into MOCK_DATA (id, name, birthday, email) values (48, 'Mei', '1967-02-22', 'mliver1b@sina.com.cn');
insert into MOCK_DATA (id, name, birthday, email) values (49, 'Vlad', '1942-11-21', 'vgimber1c@addthis.com');
insert into MOCK_DATA (id, name, birthday, email) values (50, 'Muhammad', '1961-10-31', 'mangear1d@globo.com');


```

3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
UPDATE employee
SET name = 'Nil'
birthday = '1999-05-01'
email = 'nil@gmail.com'
WHERE id = 12;

UPDATE employee
SET name = 'Ayşe'
birthday = '1999-09-10'
WHERE name LIKE 'R%'
RETURNING *;

UPDATE employee
SET  birthday = '1999-09-10'
WHERE name = 'Mei'
RETURNING *;

UPDATE employee
SET  name = 'Tolga'
WHERE id = 48
RETURNING *;

UPDATE employee
SET  name = 'örnek'
WHERE id = 3
RETURNING *;

```

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```
DELETE FROM employee
WHERE id = 5;

DELETE FROM employee
WHERE id > 20
RETURNING *;

DELETE FROM employee
WHERE name LIKE 'M%'
RETURNING *;

DELETE FROM employee
WHERE name ILIKE '%M%'
RETURNING *;

DELETE FROM employee
WHERE name LIKE '%a'
RETURNING *;

```
