<template>
  <CRow>
    <CCol>
      <h1>PROFIL PEGAWAI</h1>
      <CCard class="mb-4">
        <CCardHeader><b>Jabatan Fungsional Pranata Komputer </b></CCardHeader>
        <CCardBody>
          <CForm>
            <CFormInput type="text" id="formControlNama" label="Nama Pegawai" />
          </CForm>
          <CForm class="mt-2 mb-2">
            <CFormInput type="text" id="formControlNip" label="NIP" />
          </CForm>

          <CForm class="mt-2 mb-2">
            <label>Jabatan</label>
            <CFormSelect
              :options="[
                'Pilih Jabatan',
                { label: 'Ahli Pertama', value: '1' },
                { label: 'Ahli Muda', value: '2' },
                { label: 'Ahli Madya', value: '3' },
                { label: 'Ahli Utama', value: '4' },
              ]"
            >
            </CFormSelect>
          </CForm>

          <CForm>
            <CFormInput type="text" id="formControlUnit" label="Unit kerja" />
          </CForm>

          <CForm>
            <CFormInput
              type="text"
              id="formControlSatuan"
              label="Satuan kerja"
            />
          </CForm>

          <br />
          <CForm>
            <CButton color="dark">Submit</CButton>
          </CForm>
        </CCardBody>
      </CCard>
    </CCol>
  </CRow>
</template>

<script></script>
