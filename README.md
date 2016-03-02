# -
数据结构小程序
template<class T>
int SqList<T>::Locate(T e)
{
    for(i=0;i<length;i++)
    if(elem[i]==e)
    return i+1;
    return 0;
};
