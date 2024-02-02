// code for GFG 
pair<long long, long long> getMinMax(long long arr[], int n) {
    long long int mini=1000000000001 ;
    long long int maxi =0 ;
    // geting maximum element 
    for(int i=0 ; i<n ; i++){
        if(arr[i] >maxi){
            maxi=arr[i] ;
        }
    }
    //geting minimum element
    for(int  i=0 ; i<n ; i++){
        if(arr[i] <mini){
            mini=arr[i] ;
        }
    }
    //return in an pair
    pair<int,int>result ;
    result.first=mini ;
    result.second = maxi ;
    return result ;
}
