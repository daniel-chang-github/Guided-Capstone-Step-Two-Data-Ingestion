# Guided-Capstone-Step-Two-Data-Ingestion


azcopy login
./azcopy login --tenant-id 74faecac-fa22-4bb2-9dc9-251c7aaae145
./azcopy make 'https://dc1928134607192022test.blob.core.windows.net/dc1928134607192022test'
./azcopy copy '/Users/daniel/Desktop/Data_Engineering/Guided Capstone/data' 'https://dc1928134607192022test.blob.core.windows.net/dc1928134607192022test' --recursive![image](https://user-images.githubusercontent.com/81652137/179835809-aab0989b-fbe0-4781-9674-d004d54060bb.png)


If you get the below permission error message, make sure to give yourself the 'Storage Blob Data Owner' role. This may take up to 5 minutes to propagate.

 403 This request is not authorized to perform this operation using this permission.

![image](https://user-images.githubusercontent.com/81652137/179835842-07d00671-8194-4995-840a-903948e55998.png)
