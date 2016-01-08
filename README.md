%___ Check Signal within Buffer Range from RSEs and Write Info

function RSEs=RSEs(I,Sig1,Sig2,Sig3,Sig4,Sig5,Sig6,Sig7,Sig8,Sig9,Sig10,Sig11,Sig12)

RSEs{I,1}(1,1)=Sig1.get('AttValue','ID');
RSEs{I,1}(2,1)=Sig1.get('AttValue','Presence');
RSEs{I,1}(3,1)=Sig1.get('AttValue','Detection');
RSEs{I,1}(4,1)=Sig1.get('AttValue','Occupancy');
RSEs{I,1}(5,1)=Sig1.get('AttValue','Vehicleid');
RSEs{I,1}(6,1)=Sig1.get('AttValue','Vehiclelength');
RSEs{I,1}(7,1)=Sig1.get('AttValue','Speed');
if RSEs{I,1}(2,1)~=0
    RSEs{I,1}(8,1)=I/10;
else
     RSEs{I,1}(8,1)=0;
end
  
RSEs{I,2}(1,1)=Sig2.get('AttValue','ID');
RSEs{I,2}(2,1)=Sig2.get('AttValue','Presence');
RSEs{I,2}(3,1)=Sig2.get('AttValue','Detection');
RSEs{I,2}(4,1)=Sig2.get('AttValue','Occupancy');
RSEs{I,2}(5,1)=Sig2.get('AttValue','Vehicleid');
RSEs{I,2}(6,1)=Sig2.get('AttValue','Vehiclelength');
RSEs{I,2}(7,1)=Sig2.get('AttValue','Speed');
if RSEs{I,2}(2,1)~=0
    RSEs{I,2}(8,1)=I/10;
else
     RSEs{I,2}(8,1)=0;
end

RSEs{I,3}(1,1)=Sig3.get('AttValue','ID');
RSEs{I,3}(2,1)=Sig3.get('AttValue','Presence');
RSEs{I,3}(3,1)=Sig3.get('AttValue','Detection');
RSEs{I,3}(4,1)=Sig3.get('AttValue','Occupancy');
RSEs{I,3}(5,1)=Sig3.get('AttValue','Vehicleid');
RSEs{I,3}(6,1)=Sig3.get('AttValue','Vehiclelength');
RSEs{I,3}(7,1)=Sig3.get('AttValue','Speed');
if RSEs{I,3}(2,1)~=0
    RSEs{I,3}(8,1)=I/10;
else
     RSEs{I,3}(8,1)=0;
end

RSEs{I,4}(1,1)=Sig4.get('AttValue','ID');
RSEs{I,4}(2,1)=Sig4.get('AttValue','Presence');
RSEs{I,4}(3,1)=Sig4.get('AttValue','Detection');
RSEs{I,4}(4,1)=Sig4.get('AttValue','Occupancy');
RSEs{I,4}(5,1)=Sig4.get('AttValue','Vehicleid');
RSEs{I,4}(6,1)=Sig4.get('AttValue','Vehiclelength');
RSEs{I,4}(7,1)=Sig4.get('AttValue','Speed');
if RSEs{I,4}(2,1)~=0
    RSEs{I,4}(8,1)=I/10;
else
     RSEs{I,4}(8,1)=0;
end

RSEs{I,5}(1,1)=Sig5.get('AttValue','ID');
RSEs{I,5}(2,1)=Sig5.get('AttValue','Presence');
RSEs{I,5}(3,1)=Sig5.get('AttValue','Detection');
RSEs{I,5}(4,1)=Sig5.get('AttValue','Occupancy');
RSEs{I,5}(5,1)=Sig5.get('AttValue','Vehicleid');
RSEs{I,5}(6,1)=Sig5.get('AttValue','Vehiclelength');
RSEs{I,5}(7,1)=Sig5.get('AttValue','Speed');
if RSEs{I,5}(2,1)~=0
    RSEs{I,5}(8,1)=I/10;
else
     RSEs{I,5}(8,1)=0;
end
  
RSEs{I,6}(1,1)=Sig6.get('AttValue','ID');
RSEs{I,6}(2,1)=Sig6.get('AttValue','Presence');
RSEs{I,6}(3,1)=Sig6.get('AttValue','Detection');
RSEs{I,6}(4,1)=Sig6.get('AttValue','Occupancy');
RSEs{I,6}(5,1)=Sig6.get('AttValue','Vehicleid');
RSEs{I,6}(6,1)=Sig6.get('AttValue','Vehiclelength');
RSEs{I,6}(7,1)=Sig6.get('AttValue','Speed');
if RSEs{I,6}(2,1)~=0
    RSEs{I,6}(8,1)=I/10;
else
     RSEs{I,6}(8,1)=0;
end

RSEs{I,7}(1,1)=Sig7.get('AttValue','ID');
RSEs{I,7}(2,1)=Sig7.get('AttValue','Presence');
RSEs{I,7}(3,1)=Sig7.get('AttValue','Detection');
RSEs{I,7}(4,1)=Sig7.get('AttValue','Occupancy');
RSEs{I,7}(5,1)=Sig7.get('AttValue','Vehicleid');
RSEs{I,7}(6,1)=Sig7.get('AttValue','Vehiclelength');
RSEs{I,7}(7,1)=Sig7.get('AttValue','Speed');
if RSEs{I,7}(2,1)~=0
    RSEs{I,7}(8,1)=I/10;
else
     RSEs{I,7}(8,1)=0;
end

RSEs{I,8}(1,1)=Sig8.get('AttValue','ID');
RSEs{I,8}(2,1)=Sig8.get('AttValue','Presence');
RSEs{I,8}(3,1)=Sig8.get('AttValue','Detection');
RSEs{I,8}(4,1)=Sig8.get('AttValue','Occupancy');
RSEs{I,8}(5,1)=Sig8.get('AttValue','Vehicleid');
RSEs{I,8}(6,1)=Sig8.get('AttValue','Vehiclelength');
RSEs{I,8}(7,1)=Sig8.get('AttValue','Speed');
if RSEs{I,8}(2,1)~=0
    RSEs{I,8}(8,1)=I/10;
else
     RSEs{I,8}(8,1)=0;
end

RSEs{I,9}(1,1)=Sig9.get('AttValue','ID');
RSEs{I,9}(2,1)=Sig9.get('AttValue','Presence');
RSEs{I,9}(3,1)=Sig9.get('AttValue','Detection');
RSEs{I,9}(4,1)=Sig9.get('AttValue','Occupancy');
RSEs{I,9}(5,1)=Sig9.get('AttValue','Vehicleid');
RSEs{I,9}(6,1)=Sig9.get('AttValue','Vehiclelength');
RSEs{I,9}(7,1)=Sig9.get('AttValue','Speed');
if RSEs{I,9}(2,1)~=0
    RSEs{I,9}(8,1)=I/10;
else
     RSEs{I,9}(8,1)=0;
end

RSEs{I,10}(1,1)=Sig10.get('AttValue','ID');
RSEs{I,10}(2,1)=Sig10.get('AttValue','Presence');
RSEs{I,10}(3,1)=Sig10.get('AttValue','Detection');
RSEs{I,10}(4,1)=Sig10.get('AttValue','Occupancy');
RSEs{I,10}(5,1)=Sig10.get('AttValue','Vehicleid');
RSEs{I,10}(6,1)=Sig10.get('AttValue','Vehiclelength');
RSEs{I,10}(7,1)=Sig10.get('AttValue','Speed');
if RSEs{I,10}(2,1)~=0
    RSEs{I,10}(8,1)=I/10;
else
     RSEs{I,10}(8,1)=0;
end

RSEs{I,11}(1,1)=Sig11.get('AttValue','ID');
RSEs{I,11}(2,1)=Sig11.get('AttValue','Presence');
RSEs{I,11}(3,1)=Sig11.get('AttValue','Detection');
RSEs{I,11}(4,1)=Sig11.get('AttValue','Occupancy');
RSEs{I,11}(5,1)=Sig11.get('AttValue','Vehicleid');
RSEs{I,11}(6,1)=Sig11.get('AttValue','Vehiclelength');
RSEs{I,11}(7,1)=Sig11.get('AttValue','Speed');
if RSEs{I,11}(2,1)~=0
    RSEs{I,11}(8,1)=I/10;
else
     RSEs{I,11}(8,1)=0;
end

RSEs{I,12}(1,1)=Sig12.get('AttValue','ID');
RSEs{I,12}(2,1)=Sig12.get('AttValue','Presence');
RSEs{I,12}(3,1)=Sig12.get('AttValue','Detection');
RSEs{I,12}(4,1)=Sig12.get('AttValue','Occupancy');
RSEs{I,12}(5,1)=Sig12.get('AttValue','Vehicleid');
RSEs{I,12}(6,1)=Sig12.get('AttValue','Vehiclelength');
RSEs{I,12}(7,1)=Sig12.get('AttValue','Speed');
if RSEs{I,12}(2,1)~=0
    RSEs{I,12}(8,1)=I/10;
else
     RSEs{I,12}(8,1)=0;
end
