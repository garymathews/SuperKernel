#
# powerpc/crypto/Makefile
#
# Arch-specific CryptoAPI modules.
#

obj-$(CONFIG_CRYPTO_AES_PPC_SPE) += aes-ppc-spe.o
obj-$(CONFIG_CRYPTO_MD5_PPC) += md5-ppc.o
obj-$(CONFIG_CRYPTO_SHA1_PPC) += sha1-powerpc.o
obj-$(CONFIG_CRYPTO_SHA1_PPC_SPE) += sha1-ppc-spe.o
obj-$(CONFIG_CRYPTO_SHA256_PPC_SPE) += sha256-ppc-spe.o

aes-ppc-spe-y := aes-spe-core.o aes-spe-keys.o aes-tab-4k.o aes-spe-modes.o aes_spe_glue.o
md5-ppc-y := md5-asm.o md5_glue.o
sha1-powerpc-y := sha1-powerpc-asm.o sha1.o
sha1-ppc-spe-y := sha1-spe-asm.o sha1_spe_glue.o
sha256-ppc-spe-y := sha256-spe-asm.o sha256_spe_glue.o
