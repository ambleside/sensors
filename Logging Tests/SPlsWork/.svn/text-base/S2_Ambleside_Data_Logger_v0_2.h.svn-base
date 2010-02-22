#ifndef __S2_AMBLESIDE_DATA_LOGGER_V0_2_H__
#define __S2_AMBLESIDE_DATA_LOGGER_V0_2_H__




/*
* Constructor and Destructor
*/

/*
* DIGITAL_INPUT
*/
#define __S2_Ambleside_Data_Logger_v0_2_CONNECT_DIG_INPUT 0
#define __S2_Ambleside_Data_Logger_v0_2_DISCONNECT_DIG_INPUT 1
#define __S2_Ambleside_Data_Logger_v0_2_POST_DATA_DIG_INPUT 2


/*
* ANALOG_INPUT
*/
#define __S2_Ambleside_Data_Logger_v0_2_DATA1_ANALOG_INPUT 0
#define __S2_Ambleside_Data_Logger_v0_2_DATA2_ANALOG_INPUT 1
#define __S2_Ambleside_Data_Logger_v0_2_DATA3_ANALOG_INPUT 2
#define __S2_Ambleside_Data_Logger_v0_2_DATA4_ANALOG_INPUT 3
#define __S2_Ambleside_Data_Logger_v0_2_DATA5_ANALOG_INPUT 4
#define __S2_Ambleside_Data_Logger_v0_2_DATA6_ANALOG_INPUT 5
#define __S2_Ambleside_Data_Logger_v0_2_DATA7_ANALOG_INPUT 6
#define __S2_Ambleside_Data_Logger_v0_2_DATA8_ANALOG_INPUT 7

#define __S2_Ambleside_Data_Logger_v0_2_STATUS1_STRING_INPUT 8
#define __S2_Ambleside_Data_Logger_v0_2_STATUS1_STRING_MAX_LEN 100
CREATE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __STATUS1, __S2_Ambleside_Data_Logger_v0_2_STATUS1_STRING_MAX_LEN );
#define __S2_Ambleside_Data_Logger_v0_2_STATUS2_STRING_INPUT 9
#define __S2_Ambleside_Data_Logger_v0_2_STATUS2_STRING_MAX_LEN 100
CREATE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __STATUS2, __S2_Ambleside_Data_Logger_v0_2_STATUS2_STRING_MAX_LEN );
#define __S2_Ambleside_Data_Logger_v0_2_STATUS3_STRING_INPUT 10
#define __S2_Ambleside_Data_Logger_v0_2_STATUS3_STRING_MAX_LEN 100
CREATE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __STATUS3, __S2_Ambleside_Data_Logger_v0_2_STATUS3_STRING_MAX_LEN );
#define __S2_Ambleside_Data_Logger_v0_2_STATUS4_STRING_INPUT 11
#define __S2_Ambleside_Data_Logger_v0_2_STATUS4_STRING_MAX_LEN 100
CREATE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __STATUS4, __S2_Ambleside_Data_Logger_v0_2_STATUS4_STRING_MAX_LEN );
#define __S2_Ambleside_Data_Logger_v0_2_STATUS5_STRING_INPUT 12
#define __S2_Ambleside_Data_Logger_v0_2_STATUS5_STRING_MAX_LEN 100
CREATE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __STATUS5, __S2_Ambleside_Data_Logger_v0_2_STATUS5_STRING_MAX_LEN );
#define __S2_Ambleside_Data_Logger_v0_2_STATUS6_STRING_INPUT 13
#define __S2_Ambleside_Data_Logger_v0_2_STATUS6_STRING_MAX_LEN 100
CREATE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __STATUS6, __S2_Ambleside_Data_Logger_v0_2_STATUS6_STRING_MAX_LEN );
#define __S2_Ambleside_Data_Logger_v0_2_STATUS7_STRING_INPUT 14
#define __S2_Ambleside_Data_Logger_v0_2_STATUS7_STRING_MAX_LEN 100
CREATE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __STATUS7, __S2_Ambleside_Data_Logger_v0_2_STATUS7_STRING_MAX_LEN );
#define __S2_Ambleside_Data_Logger_v0_2_STATUS8_STRING_INPUT 15
#define __S2_Ambleside_Data_Logger_v0_2_STATUS8_STRING_MAX_LEN 100
CREATE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __STATUS8, __S2_Ambleside_Data_Logger_v0_2_STATUS8_STRING_MAX_LEN );



/*
* DIGITAL_OUTPUT
*/


/*
* ANALOG_OUTPUT
*/
#define __S2_Ambleside_Data_Logger_v0_2_CONNECT_FB_ANALOG_OUTPUT 0

#define __S2_Ambleside_Data_Logger_v0_2_OUTPUT$_FB_STRING_OUTPUT 1
#define __S2_Ambleside_Data_Logger_v0_2_RECIEVED_FB_STRING_OUTPUT 2


/*
* Direct Socket Variables
*/

#define __S2_Ambleside_Data_Logger_v0_2_AMBLESIDE_SOCKET 16
#define __S2_Ambleside_Data_Logger_v0_2_AMBLESIDE_STRING_MAX_LEN 2000
START_SOCKET_DEFINITION( S2_Ambleside_Data_Logger_v0_2, __AMBLESIDE )
{
   int SocketStatus;
   enum ESplusSocketType eSocketType;
   int SocketID;
   void *SocketPtr;
CREATE_SOCKET_STRING( S2_Ambleside_Data_Logger_v0_2, SocketRxBuf, __S2_Ambleside_Data_Logger_v0_2_AMBLESIDE_STRING_MAX_LEN );
};



/*
* INTEGER_PARAMETER
*/
/*
* SIGNED_INTEGER_PARAMETER
*/
/*
* LONG_INTEGER_PARAMETER
*/
/*
* SIGNED_LONG_INTEGER_PARAMETER
*/
/*
* INTEGER_PARAMETER
*/
/*
* SIGNED_INTEGER_PARAMETER
*/
/*
* LONG_INTEGER_PARAMETER
*/
/*
* SIGNED_LONG_INTEGER_PARAMETER
*/
/*
* STRING_PARAMETER
*/
#define __S2_Ambleside_Data_Logger_v0_2_URL_PRE_STRING_PARAMETER 10
#define __S2_Ambleside_Data_Logger_v0_2_HOST_NAME_STRING_PARAMETER 11
#define __S2_Ambleside_Data_Logger_v0_2_SENSOR_ID_STRING_PARAMETER 12
#define __S2_Ambleside_Data_Logger_v0_2_URL_PRE_PARAM_MAX_LEN 25
CREATE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __URL_PRE, __S2_Ambleside_Data_Logger_v0_2_URL_PRE_PARAM_MAX_LEN );
#define __S2_Ambleside_Data_Logger_v0_2_HOST_NAME_PARAM_MAX_LEN 50
CREATE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __HOST_NAME, __S2_Ambleside_Data_Logger_v0_2_HOST_NAME_PARAM_MAX_LEN );
#define __S2_Ambleside_Data_Logger_v0_2_SENSOR_ID_PARAM_MAX_LEN 50
CREATE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __SENSOR_ID, __S2_Ambleside_Data_Logger_v0_2_SENSOR_ID_PARAM_MAX_LEN );


/*
* INTEGER
*/


/*
* LONG_INTEGER
*/


/*
* SIGNED_INTEGER
*/


/*
* SIGNED_LONG_INTEGER
*/


/*
* STRING
*/
#define __S2_Ambleside_Data_Logger_v0_2_HEX_ARRAY_NUM_ELEMS 255
#define __S2_Ambleside_Data_Logger_v0_2_HEX_ARRAY_NUM_CHARS 3
CREATE_STRING_ARRAY( S2_Ambleside_Data_Logger_v0_2, __HEX, __S2_Ambleside_Data_Logger_v0_2_HEX_ARRAY_NUM_ELEMS, __S2_Ambleside_Data_Logger_v0_2_HEX_ARRAY_NUM_CHARS );

/*
* STRUCTURE
*/

START_GLOBAL_VAR_STRUCT( S2_Ambleside_Data_Logger_v0_2 )
{
   void* InstancePtr;
   struct GenericOutputString_s sGenericOutStr;
   unsigned short LastModifiedArrayIndex;

   unsigned short __BRXOK;
   DECLARE_STRING_ARRAY( S2_Ambleside_Data_Logger_v0_2, __HEX );
   DECLARE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __STATUS1 );
   DECLARE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __STATUS2 );
   DECLARE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __STATUS3 );
   DECLARE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __STATUS4 );
   DECLARE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __STATUS5 );
   DECLARE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __STATUS6 );
   DECLARE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __STATUS7 );
   DECLARE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __STATUS8 );
   DECLARE_SOCKET( S2_Ambleside_Data_Logger_v0_2, __AMBLESIDE );
   DECLARE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __URL_PRE );
   DECLARE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __HOST_NAME );
   DECLARE_STRING_STRUCT( S2_Ambleside_Data_Logger_v0_2, __SENSOR_ID );
};

START_NVRAM_VAR_STRUCT( S2_Ambleside_Data_Logger_v0_2 )
{
};



#endif //__S2_AMBLESIDE_DATA_LOGGER_V0_2_H__

