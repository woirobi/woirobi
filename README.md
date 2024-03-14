disp(['PEMBUKAAN']);
Y=input('y='); % default-nya bilangan reaal presisi ganda
x=single(y);   % x bilangan real presisi tunggal
k=uint32(y);   % k bilangan bulat 32 bit

disp(['awalnya k=x=y=',num2str(y),sprinf('\n\n')]);
disp(['y/3=',num2str(y/3,'%15.13f'),'<==real presisi ganda']);
disp(['x/3=',num2str(x/3,'%15.13f'),'<==real presisi tunggal']);
disp(['x/3=',nun2str(k/3),repmat    ('',[1 14]), <==integer 32 bit']);
