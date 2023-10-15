set(srcs
	"MPU6050.cpp")

idf_component_register(SRCS "${srcs}"
                       INCLUDE_DIRS "include"
					   PRIV_REQUIRES driver I2Cdev)