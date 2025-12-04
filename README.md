MODEL 1



MODEL 4
# TIMESTEP = 0.1SEC
# state 변경 12개 (1개 더미변수)
#     """
#     State Vector (예시: 13차원)
#     0:  ego_speed           (0~1, 50 km/h 기준 정규화)
#     1:  dtc_norm            (0~1, 충돌지점까지 남은 거리 / 200 m)
#     2:  time_to_Gn_norm     (0~1, GN까지 남은 시간 / 100 s)
#     3:  f1_spacing_norm     (0~1, 가장 가까운 following spacing)
#     4:  f1_ttc_norm         (0~1, 가장 가까운 following TTC)
#     5:  f1_rel_speed_norm   (~[-1,1], 가장 가까운 following 상대속도)
#     6:  f2_spacing_norm     (0~1, 두 번째 following spacing)
#     7:  f2_ttc_norm         (0~1, 두 번째 following TTC)
#     8:  c1_spacing_norm     (0~1, 가장 가까운 crossing spacing)
#     9:  c1_pet_norm         (0~1, 가장 가까운 crossing PET)
#     10: c2_spacing_norm     (0~1, 두 번째 crossing spacing)
#     11: c2_pet_norm         (0~1, 두 번째 crossing PET)
#     12: dummy_cross_rel     (~[-1,1], crossing 상대속도 자리(현재 0.0, 추후 확장용))
#     """
# following vehs 4



MODEL 5
# TIMESTEP = 1SEC
# state 변경 13개
#     """
#     State Vector (예시: 13차원)
#     0:  ego_speed           (0~1, 50 km/h 기준 정규화)
#     1:  dtc_norm            (0~1, 충돌지점까지 남은 거리 / 200 m)
#     2:  time_to_Gn_norm     (0~1, GN까지 남은 시간 / 100 s)
#     3:  f1_spacing_norm     (0~1, 가장 가까운 following spacing)
#     4:  f1_ttc_norm         (0~1, 가장 가까운 following TTC)
#     5:  f1_rel_speed_norm   (~[-1,1], 가장 가까운 following 상대속도)
#     6:  f2_spacing_norm     (0~1, 두 번째 following spacing)
#     7:  f2_ttc_norm         (0~1, 두 번째 following TTC)
#     8:  c1_spacing_norm     (0~1, 가장 가까운 crossing spacing)
#     9:  c1_pet_norm         (0~1, 가장 가까운 crossing PET)
#     10: c2_spacing_norm     (0~1, 두 번째 crossing spacing)
#     11: c2_pet_norm         (0~1, 두 번째 crossing PET)
#     12: dummy_cross_rel     (~[-1,1], crossing 상대속도 자리(현재 0.0, 추후 확장용))
#     """
# following vehs 4
