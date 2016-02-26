# bcm_wimax-64
bcm_wimax driver from linux kernel

# reasons
I created this repository to make this driver work on x86_64 bit linux kernel. 
I cannot fix error in controlling interface. If anyone can help me fix this erorr, you're welcome!

#error

CmHost.c:1387:39: warning: cast to pointer from integer of different size [-Wint-to-pointer-cast] <br>
  pstAddIndication->psfAuthorizedSet = (struct bcm_connect_mgr_params *)ntohl((ULONG)pstAddIndication->psfAuthorizedSet);<br>
CmHost.c:1426:37: warning: cast to pointer from integer of different size [-Wint-to-pointer-cast]<br>
  pstAddIndication->psfAdmittedSet = (struct bcm_connect_mgr_params *)ntohl((ULONG)pstAddIndication->psfAdmittedSet);<br>
CmHost.c:1440:35: warning: cast to pointer from integer of different size [-Wint-to-pointer-cast]<br>
  pstAddIndication->psfActiveSet = (struct bcm_connect_mgr_params *)ntohl((ULONG)pstAddIndication->psfActiveSet);<br>

