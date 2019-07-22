# MLink-LabVIEW
MLink for labview - new API

# Changes since 2.1.0
- Added timeout argument int mlink_ai_scan() 
int  mlink_ai_scan(int *link_fd, double *data, uint32_t scan_count, int32_t timeout);
Timeout argument in miliseconds shall be provided. If 0, function reads avaliable data from the queue. If -1 function wait until receives all date (inf wait) - TBD
- Functions mlink_ai_scan() and mlink_ai_scan_stop() - link_fd added - not functional - only for compatibility - TBD
- Fix mlink_dsp_signal_read() when DSP execution is finished and user try to read data. 
