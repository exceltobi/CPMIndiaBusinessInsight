SELECT        project_id AS [Project ID], emp_id AS [Employee ID], store_id AS [Store ID], storetype_id AS [Store Type ID], channel_id AS [Channel ID], chain_id AS [Chain ID], camera_allowed AS [Camera Allowed], CAST(visit_date AS datetime) 
                         AS [Visit Date], is_present AS [Is Present], brand_id AS [Brand ID], display_id AS [Display ID], Remarks, image_url AS [Image URL], CAST(project_id AS VARCHAR) + '_' + CAST(emp_id AS VARCHAR) AS ProjectID_EmpID, 
                         CAST(project_id AS VARCHAR) + '_' + CAST(store_id AS VARCHAR) AS ProjectID_StoreID, CAST(project_id AS VARCHAR) + '_' + CAST(brand_id AS VARCHAR) AS ProjectID_BrandID, CAST(project_id AS VARCHAR) 
                         + '_' + CAST(display_id AS VARCHAR) AS ProjectID_DisplayID
FROM            dbo.additional_visibility
