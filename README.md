# PiFS
Raspberry Pi Functionality Suite - Xojo

The Raspberry Pi Functionality Suite is a collection of Raspberry Pi OS (Debian) specific functionality that is not readily available in a free format. It is an open source collaboration that brings users all of the specialized Raspberry Pi functionality that is not included with Xojo/Real Studio itself. 

Notes
This code was originally written by Eugene Dakin for Xojo. 

Xojo
 - Version 2025R1.1

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
