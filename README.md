# PiFS
Raspberry Pi Functionality Suite - Xojo

The Raspberry Pi Functionality Suite is a collection of Raspberry Pi OS (Debian) specific functionality that is not readily available in a free format. It is an open source collaboration that brings users all of the specialized Raspberry Pi functionality that is not included with Xojo/Real Studio itself. 

Notes
This code was originally written by Eugene Dakin for Xojo. 

Xojo
 - Version 2025R2.1

Repository Location
Https://github.com/eugenedakin/PiFS

Versions:
Version 1.0 (9 May 2025)
- added Accept method
- added Bind method
- added Close method
- added Errno method
- added ErrnoMessage method
- added fcntl method
- added hci_devinfo method
- added hci_get_route method
- added Listen method
- added Read Method
- added selectBT method
- added Socket method
- added Write method
- added hci_dev_info structure 
- added hci_dev_stats structure 
- added sockaddr_rc structure 
- added over 35 bluetooth constants

Version 1.1 (25 May 2025)
- added Statvfs structure 
- added statvfs method

Version 1.2 (2 June 2025)
- added Timerfd_Create method
- added Timerfd_SetTime method
- added CLOCK_MONOTONIC constant
- added TFD_CLOEXEC consttant
- added TFD_NONBLOCK constant

Version 1.3 (3 June 2025)
- added clock_gettime method
- added usleep method
- added nanosleep method
- added CLOCK_REALTIME constant
- added CLOCK_PROCESS_CPUTIME_ID constant
- added CLOCK_THREAD_CPUTIME_ID constant
- added TimeSpec structure

Version 1.4 (4 June 2025)
- added Timer Methods in the PiTimer Class 
- added Elapsed Microseconds Timer Method
- added Elapsed Milliseconds Timer Method
- added GetCurrentTime Timer Method
- added IsRunning Timer Method
- added Reset Timer method
- added SleepNanoseconds Timer Method
- added Start Timer method
- added Stop Timer method
- added NanoSleep Declare
- added uSleep (microsleep) Declare

Version 1.5 (6 June 2025)
- added TimeSpec structure 
- added thread methods 
- added pthread_create Declare
- added pthread_join Declare
- added pthread_detach Declare
- added pthread_self Declare
- added pthread_exit Declare
- added sleep declare

Version 1.6 (7 June 2025)
- added gtk_application_new Declare
- added gtk_application_window_new Declare
- added gtk_widget_show_all Declare
- added gtk_window_set_default_size Declare
- added gtk_window_set_title Declare
- added g_object_unref Declare
- added g_signal_connect_data Declare
- added printf declare

Version 1.7 (8 June 2025)
- added gtk_widget_add_events Declare
- added GDK_BUTTON_PRESS_MASK Constant
- added gtk_widget_destroy Declare
- added g_application_run Declare
- added GTK_MESSAGE_INFO Constant
- added GTK_BUTTONS_OK Constant
- added GTK_DIALOG_MODAL Constant
- corrected issue in g_signal_connect_data Declare
- added gtk_widget_get_toplevel Declare
- added GTK_DIALOG_DESTROY_WITH_PARENT Constant
- added GTK_DIALOG_USE_HEADER_BAR Constant
- added GTK_MESSAGE_QUESTION Constant
- added GTK_BUTTONS_OK_CANCEL Constant
- added GTK_RESPONSE_OK Constant
- added GTK_RESPONSE_CANCEL Constant
- added gtk_dialog_new_with_buttons Declare
- added gtk_container_add Declare
- added gtk_window_set_modal Declare
- added RESPONSE_OK Constant
- added RESPONSE_CANCEL Constant
- added gtk_dialog_add_button Declare
- added gtk_dialog_get_content_area Declare
- added gtk_label_new Declare

Version 1.8 (9 June 2025)
- added gtk_widget_get_window Declare
- added gdk_cursor_new_from_name Declare
- added gdk_window_set_cursor Declare
- added gtk_widget_get_display Declare
- added gtk_window_get_window Declare
- added gtk_menu_bar_new Declare
- added gtk_menu_new Declare
- added gtk_menu_item_new_with_label Declare
- added gtk_menu_item_set_submenu Declare
- added gtk_bin_get_child Declare
- added gtk_widget_get_parent Declare
- added gtk_widget_get_name Declare
- added gtk_widget_get_ancestor Declare
- added gtk_box_pack_start Declare
- added gtk_widget_get_parent_window
- added gtk_widget_get_allocation Declare
- added gtk_window_get_titlebar Declare
- added gtk_window_list_toplevels Declare
- added g_list_nth_data Declare
- added gtk_widget_get_visible Declare
- added gtk_widget_realize Declare
- added gtk_menu_shell_append Declare
- added gtk_container_remove Declare
- added gtk_window_get_child Declare

Version 1.9 (10 June 2025)
- added g_main_context_default Declare
- added g_idle_add Declare
- added g_main_context_invoke_full Declare
- added gtk_label_set_text Declare
- added G_PRIORITY_DEFAULT_IDLE Constant

Version 1.10 (11 June 2025)
- modified constant value of G_PRIORITY_DEFAULT_IDLE
- added G_PRIORITY_HIGH Constant
- added G_PRIORITY_DEFAULT Constant
- added G_PRIORITY_HIGH_IDLE Constant
- added G_PRIORITY_LOW Constant

Version 1.11 (13 June 2025)
- added gtk_init Declare
- added gtk_window_new Declare
- added gtk_main Declare
- added gtk_box_new Declare
- added gtk_container_set_border_width Declare

Version 1.12 (14 June 2025)
- added gtk_button_new_with_label() Declare
- added gtk_button_new_with_label(cLabel) Declare
- readded g_idle_add Declare
- Changed gtk_main from a function to a sub
- added GTK_ORIENTATION_VERTICAL constant

Version 1.13 (18 June 2025)
- change gtk_container_add from Sub to Function 
- added gtk_widget_set_size_request Declare
- added gtk_fixed_new Declare
- added gtk_fixed_put Declare
- added gtk_widget_get_xid Declare
- added gtk_widget_show Declare
- changed gtk_widget_show_all from a Sub to Function 
- added gdk_x11_window_get_xid Declare
- changed gtk_widget_realize from a Sub to Function 
- added xOpenDisplay Declare
- added XFindWindow Declare
- added gtk_container_get_children Declare
- added gtk_window_get_title Declare
- added GTK_ORIENTATION_HORIZONTAL Constant 
- added g_main_context_get_default Declare

Version 1.14 (19 June 2025)
- added O_WRONLY Constant
- added O_CREAT Constant
- added O_TRUNC Constant
- added S_IRUSR Constant
- added S_IWUSR Constant
- modified Open Declare 
- Overload Write Declare

Version 1.15 (21 June 2025)
- added gtk_file_chooser_dialog_new Declare
- added gtk_file_chooser_get_filename Declare
- added GTK_FILE_CHOOSER_ACTION_SAVE Constant
- added GTK_RESPONSE_ACCEPT Constant
- added g_free Declare
- added S_IXUSR Constant
- added S_IRWXU Constant
- added S_IRGRP Constant
- added S_IWGRP Constant
- added S_IXGRP Constant
- added S_IRWXG Constant
- added S_IROTH Constant
- added S_IWOTH Constant
- added S_IXOTH Constant
- added S_IRWXO Constant
- added O_RDONLY Constant
- added RDWR Constant
- added O_EXCL Constant
- added O_NOCTTY Constant
- added O_APPEND Constant
- added O_NONBLOCK Constant
- added O_SYNC Constant
- added O_DSYNC Constant
- added O_CLOEXEC Constant

Version 1.16 (22 June 2025)
- Overloaded Open Declare
- Overloaded Close Declare
- added stat structure 
- added fstat Declare
- added GTK_FILE_CHOOSER_ACTION_OPEN

Version 1.17 (28 June 2025)
- added ST_RDONLY Constant
- added ST_NOSUID Constant
- added ST_NODEV Constant
- added ST_NOEXEC Constant
- added ST_SYNCHRONOUS Constant
- added ST_MANDLOCK Constant
- added ST_WRITE Constant
- added ST_APPEND Constant
- added ST_IMMUTABLE Constant
- added ST_NOATIME Constant
- added ST_NODIRATIME Constant
- added ST_RELATIME Constant

Version 1.18 (29 June 2025)
- added unlink Declare
- added GTK_MESSAGE_WARNING as Number Constant

Version 1.19 (31 July 2025)
- added gtk_x11_window_get_xid Declare
- added gtk_widget_set_opacity Declare
- added gdk_window_set_opacity Declare 
- added GTK_WINDOW_TOPLEVEL constant 
- added gtk_window_set_decorated Declare
- added gtk_window_move Declare
- added gtk_window_set_resizable Declare
- added wl_display_connect Declare
- added GTK_WINDOW_POPUP Constant
- added gdk_wayland_window_get_wl_surface Declare
- added gtk_window_set_type_hint Declare
- added GDK_WINDOW_TYPE_HINT_UTILITY Constant
- added gdk_window_move Declare

Version 1.20 (23 August 2025)
- added gst_init Declare
- added gst_element_set_state Declare
- added gst_object_unref Declare
- added gst_element_factory_make Declare
- added g_object_set Declare
- added GST_STATE_NULL Constant
- added GST_STATE_PAUSED Constant
- added GST_STATE_PLAYING Constant
- added GST_STATE_READY Constant
- added GST_STATE_VOID_PENDING Constant

Version 1.21 (24 August 2026)
- added gst_element_query_position Declare
- added  gst_element_query_duration Declare
- added GST_FORMAT_TIME Constant
- added GST_SEEK_FLAG_ACCURATE Constant
- added GST_SEEK_FLAG_FLUSH Constant
- added gst_element_seek Declare
- added custom method to convert seconds to Minutes:Seconds (FormatSecondsToMinuteSeconds)
