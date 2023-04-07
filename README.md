# CTDL-GT_Interchange_Sort_1.cpp
Interchange Sort 
Nguồn tham khảo: https://gochocit.com/ky-thuat-lap-trinh/thuat-toan-sap-xep-doi-cho-truc-tiep-interchange-sort
Cài đặt thuật toán: 

void Interchange_Sort(int a[], int n)
{
	int i,j;
	for(i=0; i<n-1; i++)
  {
		for(j=i+1; j<n; j++)
    {
			if(a[i]>a[j])
      {
				swap(a[i],a[j]);//đổi chỗ chúng nó:  a[i] và a[j]
			}
		}
	}
}
