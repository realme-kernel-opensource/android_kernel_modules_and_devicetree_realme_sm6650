PINEAPPLE_BASE_DTB += ../qcom/pineapple.dtb ../qcom/pineapple-v2.dtb ../qcom/cliffs.dtb ../qcom/cliffs7.dtb ../qcom/volcano.dtb ../qcom/volcano6.dtb ../qcom/volcano6i.dtb
PINEAPPLE_APQ_BASE_DTB += ../qcom/pineapplep.dtb ../qcom/pineapplep-v2.dtb

OPLUS_PINEAPPLE_BOARDS += enzo-23607-pineapple-overlay.dtbo\
                          bale-23609-cliffs-overlay.dtbo\
                          bale-23622-cliffs-overlay.dtbo\
                          bale-23718-cliffs-overlay.dtbo\
                          bale-24687-cliffs-overlay.dtbo\
                          divo-23631-pineapple-overlay.dtbo\
                          divo-23631-pineapple-overlay-EVT1.dtbo\
                          divo-24672-pineapple-overlay.dtbo\
                          divo-24602-pineapple-overlay.dtbo\
                          piaget-24607-volcano-overlay.dtbo\
                          piaget-24623-volcano-overlay.dtbo\
                          piaget-24698-volcano-overlay-Amazon.dtbo\
                          piaget-24697-volcano-overlay.dtbo\
                          piaget-24698-volcano-overlay-EU.dtbo\
                          piaget-24698-volcano-overlay.dtbo\
                          dongfeng-24718-volcano-overlay.dtbo\
                          dongfeng-24744-volcano-overlay-EU.dtbo\
                          dongfeng-24744-volcano-overlay.dtbo\
                          dongfeng-24612-volcano-overlay.dtbo\
                          dongfeng-24771-volcano-overlay-EU.dtbo\
                          dongfeng-24772-volcano-overlay.dtbo

dtb-y += $(OPLUS_PINEAPPLE_BOARDS) $(PINEAPPLE_BASE_DTB) $(PINEAPPLE_APQ_BASE_DTB)

always-y	:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
